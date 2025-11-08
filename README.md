# ⚡ Tkinter JSON Code Generator [v0.1]

A web-based tool built using vanilla JavaScript and Tailwind CSS that generates ready-to-use **Python Tkinter code** from a simple JSON structure, utilizing the `place` geometry manager.

## Live Demo
Since this is a client-side web application, you can use it instantly!

[**👉 Click here to launch the Tkinter Code Generator**  https://edamisirlioglu.github.io/tkinter-json-codegen/]

---

## Key Features

* **JSON Schema Validation:** Ensures the uploaded design file strictly adheres to the expected JSON format before code generation.
* **Component Support:** Generates code for common Tkinter widgets, including `Window`, `Label`, `Button`, `Entry`, `Checkbutton`, `Radiobutton`, and `Listbox`.
* **Automatic Handlers:** Automatically defines placeholder Python functions for any specified widget `command` events.
* **Full Theming:** Includes a toggle for Light and Dark modes.
* **Instant Download:** Allows direct download of the generated code as a ready-to-run `.py` file.

---

## How to Use

1.  **Prepare Design:** Create your UI design in a simple JSON file (see the expected format below).
2.  **Upload:** Click **"Upload JSON Design File"** and select your `.json` file.
3.  **Generate:** Click the **"Generate & Validate Code"** button. The Python code will instantly appear on the right side.
4.  **Download:** Click **"Download Python (.py)"** to save the file and run your Tkinter application locally.

### Expected JSON Format Example

```json
[
  { "type": "Window", "width": 800, "height": 600, "title": "Application Name" },
  { "type": "Label", "text": "Username:", "x": 50, "y": 50 },
  { "type": "Button", "text": "Log In", "x": 160, "y": 100, "command": "login_handler" }
]
```

---

## Tech Stack

1. Frontend Logic: Vanilla JavaScript

2. Styling: Tailwind CSS

3. Syntax Highlighting: Prism.js

4. Validation: AJV (JSON Schema Validator)

5. Code Output: Python Tkinter
