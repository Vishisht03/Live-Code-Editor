# Live Code Editor

A simple live code editor for HTML, CSS, and JavaScript with real-time output.

## Features

- **Real-time Preview**: Automatically updates the output as you type.
- **Separate Panels**: Dedicated panels for HTML, CSS, and JavaScript.
- **Embedded Output**: Displays the live preview in an iframe.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **Font Awesome** for icons

## How to Use

1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    ```

2. **Open `index.html` in a web browser**.

3. **Start Coding**:
    - Write HTML in the HTML panel.
    - Write CSS in the CSS panel.
    - Write JavaScript in the JavaScript panel.
    - The output will be displayed in the right panel in real-time.

## File Structure

- `index.html`: The main HTML file containing the structure of the code editor.
- **CSS**:
    - Styles for the layout and design of the editor.
- **JavaScript**:
    - Handles real-time updating of the output.

## Code Overview

- **HTML**:
    - Defines the layout with a container divided into two sections: left (code inputs) and right (output).

- **CSS**:
    - Basic styling for layout, fonts, and colors.

- **JavaScript**:
    - `run()` function:
        - Reads the content of the HTML, CSS, and JavaScript panels.
        - Updates the content of the iframe with the HTML and CSS.
        - Evaluates the JavaScript code within the iframe.

## External Resources

- **Font Awesome**: Used for icons in the labels.

## Future Improvements

- **Add Download/Save**: Ability to download the written code.
- **Error Handling**: Display errors from the JavaScript panel.
- **Resizing Panels**: Make the code and output panels resizable.

## Contributions

Contributions, issues, and feature requests are welcome!

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

