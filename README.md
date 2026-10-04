# JavaScript Fundamentals Playground

![GitHub repo size](https://img.shields.io/github/repo-size/imaakarsh/Js) ![License](https://img.shields.io/github/license/imaakarsh/Js) ![Node.js version](https://img.shields.io/badge/node-%3E%3D14-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

**Live Demo**: — | **Issues**: [GitHub Issues](https://github.com/imaakarsh/Js/issues) | **Pull Requests**: [GitHub PRs](https://github.com/imaakarsh/Js/pulls)

`Js` is a curated collection of bite‑size JavaScript snippets that illustrate core language concepts—from variables and data types to advanced topics like prototypes, classes, and symbols. It is designed for:

* **Beginners** who want to see each concept in isolation.
* **Instructors** looking for ready‑made examples for workshops or cohort sessions.
* **Anyone** who needs a quick reference while learning or teaching JavaScript.

All examples are runnable with Node.js or directly in the browser, and are organized into logical folders like `BackToBasic.js`, `Cohort`, `JavaScript`, `Part 1 Js`, and `Part 2 JS` for easy navigation.

---

## Features

| Category | Files | Description | Status |
| --- | --- | --- | --- |
| **Basics** | `JavaScript/test.js`, `BackToBasic.js/hello.js`, `Cohort/01-console.js` | Simple console output, environment tests, and basic function definitions. | ✅ Stable |
| **Variables & Types** | `BackToBasic.js/01_Varialble.js`, `02_datatypes.js`, `datatypes_symry.js`, `JavaScript/01_Variables.js`, `02_DataTypes.js` | Declaration, scope (global, block, functional), strict mode, and primitive vs reference types. | ✅ Stable |
| **Conversions & Operations** | `BackToBasic.js/03_ConversionOperation.js` | Arithmetic operators, negative values, assignment operators, and type conversion logic. | ✅ Stable |
| **Comparisons & Logic** | `BackToBasic.js/04_Comprision.js`, `Cohort/06-conditional.js` | Equality (`==`, `===`), relational operators, logical operators (`&&`, `||`, `!`), and conditional flow control. | ✅ Stable |
| **Strings** | `BackToBasic.js/05_Strings.js`, `Cohort/05-Strings.js` | Template literals, string methods, and Unicode handling. | ✅ Stable |
| **Numbers & Math** | `BackToBasic.js/06_NumbsAndMaths.js`, `Cohort/04-number.js` | `Number` object, locale formatting, and numeric utilities. | ✅ Stable |
| **Dates & Time** | `BackToBasic.js/07_Dates.js` | Date object manipulation and formatting. | ✅ Stable |
| **Arrays & Methods** | `BackToBasic.js/08_Array.js`, `Cohort/07-array.js`, `08-array-methods.js` | Creation, iteration, and higher‑order methods. | ✅ Stable |
| **Objects & Prototypes** | `Cohort/09-objects.js`, `10-Object-Methods.js`, `13-new.js`, `14-prototype.js` | Literal objects, constructors, method definitions, and prototype chain. | ✅ Stable |
| **`this` & Context** | `Cohort/11-this.js`, `12-call-bind-apply.js` | Context binding patterns and function methods. | ✅ Stable |
| **Classes & Inheritance** | `Cohort/15-Classes.js` | ES6 class syntax, constructors, and inheritance. | ✅ Stable |
| **Symbols** | `Cohort/16-symbol.js` | Unique identifiers and well‑known symbols. | ✅ Stable |
| **Cohort Index** | `Cohort/index.js` | Small demo of variable declarations. | ✅ Stable |
| **DOM & Web Integration** | `Part 1 Js/index.html`, `Part 1 Js/script.js`, `Part 2 JS/index.html`, `Part 2 JS/script.js` | DOM manipulation, selecting elements, modifying text/HTML, dynamic CSS styling, attribute manipulation, and class list operations. | ✅ Stable |

---

## Tech Stack

| Layer | Technology | Reason |
| --- | --- | --- |
| **Runtime** | **Node.js** (v14+) | Executes all examples without a browser. |
| **Language** | **JavaScript (ES2022)** | Modern syntax (let/const, arrow functions, classes). |
| **Package Manager** | **npm** (optional) | For installing development tools (e.g., ESLint). |
| **Container (optional)** | **DevContainer** (`.devcontainer/devcontainer.json`) | Provides a ready‑to‑code VS Code environment. |

---

## Project Structure

```text
Js/
├─ .devcontainer/          # VS Code DevContainer definition
├─ .github/                # GitHub config (Dependabot)
├─ 01_basic/               # Very first “Hello World” style script
├─ BackToBasic.js/         # Core fundamentals (variables → maths)
│   ├─ 01_Varialble.js
│   ├─ 02_datatypes.js
│   ├─ 03_ConversionOperation.js
│   ├─ 04_Comprision.js
│   ├─ 05_Strings.js
│   ├─ 06_NumbsAndMaths.js
│   ├─ datatypes_symry.js
│   └─ hello.js
└─ Cohort/                 # Structured lesson files used in a cohort setting
    ├─ 01-console.js
    ├─ 02-variables.js
    ├─ … (01‑16)
    ├─ README.md           # Cohort‑specific readme
    ├─ index.js
    └─ tempCodeRunnerFile.js
```

Each file is a self-contained example that can be executed with `node <path>`.

---

## Requirements

| Tool | Minimum Version |
| --- | --- |
| **Git** | 2.20+ |
| **Node.js** | 14.x (LTS) |
| **npm** (bundled with Node) | 6.x+ |
| **VS Code** (optional) | 1.70+ (for DevContainer) |

---

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/imaakarsh/Js.git
   cd Js
   ```

2. (Optional) Install dev dependencies for linting / testing:

   ```bash
   npm install
   ```

### Verify the Setup

```bash
node -v   # should print v14.x or newer
npm -v    # should print a version >=6
```

---

## Usage

### Running a Single Example

To run a script using Node.js:

```bash
node BackToBasic.js/01_Varialble.js
```

### Running Browser Examples

To view browser-based examples, open the HTML files in your browser:

```bash
# Open Part 1
open "Part 1 Js/index.html"

# Open Part 2 (DOM Manipulation)
open "Part 2 JS/index.html"

# Windows equivalent for Part 2
start "" "Part 2 JS\index.html"

# Open index.html in your default browser
open JavaScriptEverything/index.html

# On macOS
open "Namaste JavaScript/index.html"

# On Windows
start "Namaste JavaScript/index.html"
```

*Note: Linux users (or any OS) can also use a live-server extension or any HTTP server. The `Part 2 JS` folder contains a simple HTML page (`index.html`) and a script (`script.js`) that demonstrate basic DOM manipulation, styling, and event handling.*

### Example: Numbers & Math Utilities

Command:

```bash
node BackToBasic.js/06_NumbsAndMaths.js
```

Expected output:

```text
400
[Number: 100]
3
10,000
```

### Quick Reference for Popular Snippets

| Command | What you’ll see |
| --- | --- |
| `node JavaScript/test.js` | Simple console environment test |
| `node BackToBasic.js/05_Strings.js` | String concatenation, template literals, length, etc. |
| `node Cohort/15-Classes.js` | Class definition, inheritance, method overriding |
| `node Cohort/12-call-bind-apply.js` | Demonstrates `call`, `apply`, `bind` usage |

### Running All Examples

Use a Bash loop to run all `.js` files and print a header before each:

```bash
for f in $(git ls-files '*.js' | grep -v 'node_modules'); do
  echo "=== $f ==="
  node "$f"
  echo
done
```

---

## API Documentation

Not applicable. The repository consists of independent scripts, not a reusable library or HTTP service.

---

## Development

### Setting up the DevContainer (VS Code)

1. Open the repository folder in VS Code.
2. When prompted, click **Reopen in Container**.
3. The container will install Node.js and expose a terminal ready for use.

### Code Style

* Use `const` for values that never change, `let` for re-assignable variables.
* Prefer arrow functions for callbacks unless you need a custom `this`.
* Follow the Airbnb JavaScript Style Guide (or your own team's guide).

### Linting & Formatting

```bash
npm run lint      # runs ESLint (configured in package.json)
npm run format    # runs Prettier
```

*(If `package.json` does not exist yet, initialize one with `npm init -y` and add ESLint/Prettier as dev dependencies.)*

---

## Tests

The repo currently contains no automated tests, but you can add Jest or Mocha tests for any file:

```bash
npm install --save-dev jest
npx jest
```

---

## Deployment

This repository is educational material and does not require deployment. If you wish to host the examples on a static site (e.g., GitHub Pages):

1. Convert each `.js` file into an HTML page with a `<script>` tag.
2. Push the generated `docs/` folder to the `gh-pages` branch.

---

## Troubleshooting

| Problem | Solution |
| --- | --- |
| `node: command not found` | Install Node.js from https://nodejs.org and ensure it’s on your `PATH`. |
| Script prints `undefined` or throws `ReferenceError` | Verify you’re using the correct file path and that the file contains valid JavaScript. |
| VS Code DevContainer fails to start | Make sure Docker Desktop is running and that you have at least 2 GB of RAM allocated to Docker. |
| Linter errors about `no-undef` | Ensure you declared variables with `let`/`const` before using them. |

### FAQ

* **Q: Do I need a package manager?**
  * **A**: Only if you want to use the optional linting/formatting tools. The core examples run with plain Node.js.

* **Q: Can I run these examples in a browser?**
  * **A**: Yes, but you’ll need to wrap them in `<script>` tags or use a bundler like Webpack/Vite.

---

## Roadmap

| Milestone | Target Date | Description |
| --- | --- | --- |
| **v1.1** | Q3 2026 | Add a `package.json` with scripts (`lint`, `format`, `test`). |
| **v1.2** | Q4 2026 | Introduce a small interactive web UI to browse examples. |
| **v2.0** | 2027 | Convert the collection into an npm package (`js-playground`) with exported utility functions. |
| **Community** | Ongoing | Accept community‑submitted examples for newer ECMAScript features (e.g., `async/await`, `Proxy`). |

---

## Contributing

We welcome contributions of any kind—new examples, typo fixes, or improved documentation.

1. Fork the repository.
2. Create a branch for your change: `git checkout -b feature/awesome-example`
3. Add / modify files. Keep the same folder organization (e.g., new topic → new file in `BackToBasic.js/` or `Cohort/`).
4. Run the linter (`npm run lint`) and ensure the script runs without errors.
5. Commit with a clear message: `git commit -m "Add example for Set & WeakSet"`
6. Push to your fork and open a Pull Request against `main`.

### Pull-Request Checklist

- [ ] Code follows the project's style guide.
- [ ] Example runs successfully (`node <file>`).
- [ ] README (or relevant section) updated if a new topic is added.
- [ ] No sensitive information (API keys, passwords) is committed.

---

## License & Credits

**License**: MIT © 2026 [Akarsh Kumar](https://github.com/imaakarsh)

### Contributors

| Name | GitHub |
| --- | --- |
| Akarsh Kumar | [imaakarsh](https://github.com/imaakarsh) |

### Acknowledgments

* Inspired by the classic “JavaScript for Beginners” tutorials.
* Thanks to the open-source community for tools like Node.js, ESLint, and Prettier.