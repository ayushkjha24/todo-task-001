# Todo List Web App

## Overview
A minimal, fast, and accessible todo-list web app you can open directly in your browser. It supports:
- Adding and removing todos instantly
- A customizable header image via URL query parameter (?url=...)
- A safe default sample image when none is provided
- Lightweight, no dependencies, and persists todos locally via localStorage

The app is designed to load fast and let you add/remove items within seconds.

## Setup
No build step or server required.

- Clone or download the repository.
- Open index.html in any modern browser.

Optional: You can also serve it locally (for example):
- Python 3: python -m http.server 8080 and open http://localhost:8080

## Usage
- Type a task into the input field and press Add (or Enter) to create a todo.
- Click Remove to delete a todo.
- Task count is shown at the top right.

Custom header image:
- Provide an image URL via the url query parameter.
- Example:
  - index.html?url=https%3A%2F%2Fpicsum.photos%2F800%2F300
- Allowed URL schemes: http, https, and data:image/... URIs.
- If the provided URL is invalid or fails to load, a built-in SVG placeholder is used automatically.

Persistence:
- Todos are saved in your browser’s localStorage and will reappear on reload.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.