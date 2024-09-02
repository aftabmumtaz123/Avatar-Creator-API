# Avatar Generator with DiceBear API

This is a simple Node.js application using Express and EJS that allows users to generate avatars using the [DiceBear Avatars API](https://www.dicebear.com). Users can select different avatar styles, and the application will display the corresponding SVG image.

## Features

- **Avatar Selection:** Users can choose from different avatar styles provided by the DiceBear API.
- **Dynamic SVG Display:** The selected avatar style is rendered dynamically on the webpage.
- **Simple and Clean UI:** The interface is designed with a focus on simplicity and ease of use.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/download/) installed on your machine.

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/aftabmumtaz123/Avatar-Creator-Api.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd avatar-generator
    ```

3. **Install the required dependencies:**
    ```bash
    npm install
    ```

4. **Run the application:**
    ```bash
    npm start
    ```

5. **Open your browser and navigate to:**
    ```
    http://localhost:3000
    ```

## Usage

1. Open the application in your browser.
2. Select an avatar style from the dropdown menu.
3. Click the "Generate Avatar" button to view the avatar.
4. If you don't select any avatar style, an error message will prompt you to select one.

## Example Avatar Styles

- **Avataaars**
- **Bottts**
- **Gridy**
- **Identicon**
- **Micah**

These styles correspond to the types you can select in the application.

## Project Structure

```plaintext
.
├── views
│   └── index.ejs   # The main view file
├── node_modules    # Node.js modules (auto-generated)
├── package.json    # Project configuration and dependencies
├── package-lock.json  # Auto-generated dependency tree
└── app.js          # Main application file

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- **[DiceBear Avatars API](https://www.dicebear.com)** for providing a wide range of customizable avatars.
- **[Express.js](https://expressjs.com)** for the minimal and flexible Node.js web application framework.
- **[EJS](https://ejs.co)** for the powerful templating language used to render the views.

## Contributing

Contributions are welcome! If you'd like to contribute, please feel free to submit a pull request or open an issue on GitHub. Whether it's improving documentation, adding new features, or fixing bugs, all contributions are appreciated.

## Contact

For any inquiries or questions, please contact [Aftab Mumtaz](mailto:aftabmumtaz14@gmail.com).

### Note:
- Replace `"https://github.com/aftabmumtaz123/Avatar-Creator-Api.git"` with the actual URL of your GitHub repository.
- Make sure to include any additional information specific to your project if needed.

This README will provide a clear overview of your project and instructions for others to install, use, and contribute to it.
