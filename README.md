# DevPulse

DevPulse is a Python package and Visual Studio Code extension that delivers instant, clear explanations for Python errors and terminal commands using Google Gemini models. With DevPulse, you can run your Python files and receive immediate, human-friendly explanations for any errors, helping you debug and learn faster.

---

## Features

- **AI-Powered Error Explanations:** Instantly translates Python errors into plain English, right after your code runs.
- **Seamless CLI Integration:** Use `devpulse run your_script.py` to get error explanations directly in your terminal.
- **VS Code Extension:** Right-click any Python file and select "Run with DevPulse (Explain Errors)" for instant feedback within your editor.
- **Easy API Key Management:** Set your Gemini API key via `.env` or directly from the VS Code command palette.
- **Works with Any Project:** No special setup required—just install and go.

---

## Installation

Install DevPulse from PyPI:

```sh
pip install devpulse
```

---

## Usage

### CLI

Run any Python script and get instant error explanations:

```sh
devpulse run your_script.py
```

You can also explain a specific error or command:

```sh
devpulse explain --text "NameError: name 'l' is not defined" --type error
devpulse explain --text "ls -la" --type command
```

### VS Code Extension

1. Install the DevPulse AI extension from the VS Code Marketplace.
2. Right-click any Python file in the Explorer.
3. Select **"Run with DevPulse (Explain Errors)"**.
4. If an error occurs, DevPulse will print an explanation immediately after the error message in the terminal.

---

## Configuration

1. Obtain your Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Create a `.env` file in your project root:
    ```
    GOOGLE_API_KEY=your_gemini_api_key_here
    ```
3. Alternatively, set your API key from the VS Code command palette:  
   Open the palette and search for **"DevPulse: Set Gemini API Key"**.

---

## Requirements

- Python 3.7 or higher
- Google Gemini API key

---

## License

MIT License

---

## Author

Abiodun  
[beeboyabiodun111@gmail.com](mailto:beeboyabiodun111@gmail.com)

---

## Contributing

Contributions and issues are welcome!  
See the [GitHub repository](https://github.com/beeboy11/devpulse) for details.
