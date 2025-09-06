# HTML5-login-shortcut
A simple custom extension to make login elements in HTML using quick commands, made by ⭐artst.


# Auto UI Generator

A simple custom extension to make login elements in HTML or React with quick commands.  
Made by ⭐artst.

Got it 👍 — here’s a **clean README.md** you can copy directly into your project (no ChatGPT notes, just content).

---

````markdown
# Auto UI Generator

A simple custom extension to make login elements in HTML or React with quick commands.  
Made by ⭐artst.

---

## Features
- Insert a **login form** instantly (`Create Login App`).
- Works in **HTML** and **React/TSX**.
- Snippet trigger: type `*create_login_app` and hit **Tab**.

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/artst/auto-ui-gen.git
````

2. Open the folder in **Visual Studio Code**.
3. Install dependencies:

   ```bash
   npm install
   ```
4. Compile the extension:

   ```bash
   npm run compile
   ```
5. Press **F5** in VS Code to launch a new Extension Development Host window.

---

## Usage

* Open a `.html` or `.tsx` file.
* Type `*create_login_app` → press **Tab**.
* Or run the command **“Create Login App”** from the Command Palette (`Ctrl+Shift+P`).

---

## Example Output

### HTML

```html
<form class="login-form">
  <h2>Login</h2>
  <input type="email" placeholder="Email" required />
  <input type="password" placeholder="Password" required />
  <button type="submit">Login</button>
</form>
```

### React / TSX

```tsx
export default function Login() {
  return (
    <form className="login-form">
      <h2>Login</h2>
      <input type="email" placeholder="Email" required />
      <input type="password" placeholder="Password" required />
      <button type="submit">Login</button>
    </form>
  );
}
```

---

## Development

* Run `npm run watch` during development to auto-compile.
* Package the extension with:

# DEBUG  
```bash
  npm run package
  ```
* This creates a `.vsix` file you can install in VS Code.

# PREVIEW CODES
<img width="668" height="403" alt="image" src="https://github.com/user-attachments/assets/f9e17800-0812-47b0-9d2d-8c41daf61ef5" />
