# Obsidian Code Editor

https://github.com/Manavalan2517/Obsidian---Code-Editor/assets/112639423/1a548fff-75e5-4fe6-931e-97b5cc456497

A simple yet customizable code editor built using Tkinter, inspired by the aesthetics of Obsidian.  This project leverages the `tklinenums` library for line number integration and `idlelib` for syntax highlighting.

## Features

* **Syntax Highlighting:** Supports highlighting for common programming constructs like comments, keywords, built-in functions, strings, definitions, and numbers.
* **Line Numbers:** Integrated line numbers for easy code navigation.
* **Customizable Themes:**  Easily switch between light and dark themes (Tokyo Night and Tokyo Light included) by modifying the `settings.json` file.  Themes define colors for various UI elements and syntax highlighting.
* **Clean UI:**  Minimalist design for a focused coding experience.


## Installation

1. **Prerequisites:** Ensure you have Python 3 installed.
2. **Clone the Repository:**
   ```bash
   git clone https://github.com/Manavalan2517/Obsidian---Code-Editor.git
   ```
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the application:**  Navigate to the project directory and execute the main Python script (the specific script isn't provided in the given files, but assuming it's named `main.py`):
   ```bash
   python main.py
   ```
2. **Switching Themes:**  Modify the `themePath` value in `Obsidian/themes/settings.json` to point to the desired theme JSON file (e.g., `"./Themes/tokyo-light.json"`).


## Customization

* **Themes:**  Create your own themes by duplicating one of the existing theme JSON files and modifying the color values.  The theme files use hexadecimal color codes.  Refer to the existing themes for the available color keys.
* **Font:**  Change the font in the `editor.py` file by modifying the `font` argument in the `self.configure` call.

## Contributing

Contributions are welcome!  Feel free to open issues and pull requests.


## Acknowledgements

* `tklinenums`:  For providing the line numbers functionality.
* `idlelib`: For providing the syntax highlighting functionality.


## Potential Improvements (For Future Development)

* **File Handling:** Implement file opening, saving, and closing features.
* **More Languages:** Extend syntax highlighting to support more programming languages.
* **Autocompletion:**  Add autocompletion functionality for enhanced coding efficiency.
* **Search and Replace:** Implement search and replace within the editor.
* **Code Folding:** Add code folding capabilities to manage complex code structures.


This enhanced README provides a more comprehensive overview of the Obsidian Code Editor, including installation instructions, usage details, customization options, contribution guidelines, and potential future improvements. It also incorporates the provided GIF demo and clarifies the project's purpose and features. Remember to replace `main.py` with the actual name of your main script.
