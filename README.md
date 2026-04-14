# 霓虹 CodeSensei - Cyberpunk Edition

CodeSensei is a premium, single-page, serverless AI coding assistant wrapped in a high-contrast Cyberpunk visual aesthetic. Built entirely using Vanilla HTML, CSS, and JavaScript, CodeSensei leverages the power of Groq's high-speed inference API (`llama-3.3-70b-versatile`) to instantly analyze, execute, and synthesize code architectures without the need for a dedicated backend compiler.

## 🚀 Features

*   **Cyberpunk UI:** High-fidelity neon aesthetic featuring micro-animations, authentic glitch text, glassmorphism, and a robust dual-pane layout.
*   **Deep Neural Code Review:** Uncover hidden bugs, optimize performance, and calculate exact Big O Time/Space matrices alongside Cyclomatic Complexity scoring.
*   **AI-Simulated Code Runner:** Mentally executes your scripts via LLM inference simulating an authentic CLI sandbox. Includes a fully functional manual **STDIN port** for interactive input simulation.
*   **Algorithm Synthesizer:** Provide a logic or algorithmic word problem, and the AI will output the explicit Big-O mathematical constraints, process architecture, and the fastest compiling payload.
*   **Line-by-Line Decryption:** Instantly translates highly complex spaghetti code into readable, plain-English instructions.
*   **Multi-Language Matrix:** Built-in syntax highlighting and architecture support for 16 languages including C, C++, Python, JavaScript, Rust, Go, and even Bash scripts.

## 🛠️ Technology Stack

*   **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+).
*   **Styling:** Custom CSS design system (No external frameworks).
*   **AI Engine:** Groq API natively executing `llama-3.3-70b-versatile`.
*   **Syntax Engine:** highlight.js (Atom One Dark theme).
*   **Assets:** Lucide icons, Google Fonts (Orbitron, Rajdhani, Fira Code).

## ⚡ How to Run

Because CodeSensei is 100% serverless, you do not need Node.js, Python, or Docker to run the environment.
1. Clone the repository.
2. Open `index.html` directly in any modern web browser.
3. *Optional:* To avoid CORS policies entirely, host locally via Python:
   ```bash
   python3 -m http.server 3000
   ```

*Note: Ensure your Groq API Key is actively integrated inside the `API_KEY` constant within `index.html`.*

## 🔮 Future Explorations

*   **Piston Execution Engine:** Replacing the AI Simulator sandbox with an authentic `Piston API` integration to physically compile and run the backend payloads inside a secure dockerized environment.
*   **Local Storage Memory:** Caching previously queried algorithms and STDIN inputs using the browser's `localStorage` matrix so data persists securely between application reloads.
*   **Multi-File Projects:** Extending the DOM capabilities to support tree-view multi-file algorithmic questions instead of single-file payloads.
