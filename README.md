# 🦴 Caveman

High-density token optimization suite and conversational compression engine for Antigravity AI agents and developer CLIs.

Cuts LLM output token costs by **60% to 75%** by stripping conversational fluff, pleasantries, and hedging while retaining 100% technical accuracy.

---

## ⚡ Features

* **Zero-Fluff Conversational Engine:** Eliminates preamble, filler adverbs, and pleasantries.
* **Preserves Technical Precision:** File paths, shell options, code syntax, and logic qualifiers remain completely untouched.
* **Sub-Skill Suite:**
  * `caveman-commit`: Generates concise conventional git commits from working diffs.
  * `caveman-review`: High-density code review targeting bugs and vulnerabilities.
  * `caveman-compress`: Strips runtime logs, stack traces, and noise into compact causal tokens.
  * `caveman-help`: Quick command reference.
* **Tiered Intensities:** `lite`, `full` (default), and `ultra`.

---

## 🚀 Installation

### Option 1: Global Plugin (All Projects on Machine)

Clone into your global Antigravity plugins directory:

```bash
# Linux / macOS / WSL
git clone https://github.com/<your-username>/caveman.git ~/.gemini/config/plugins/caveman

# Windows PowerShell
git clone https://github.com/<your-username>/caveman.git "$HOME\.gemini\config\plugins\caveman"
```

### Option 2: Project-Specific (Team Shared)

Add directly to your repository's `.agents/` folder:

```bash
mkdir -p .agents/plugins
git submodule add https://github.com/<your-username>/caveman.git .agents/plugins/caveman
```

---

## 📖 Usage

### Activate via Slash Command
Type in chat:
* `/caveman` — Enable default Caveman mode.
* `/caveman lite` — Zero filler words, full sentences.
* `/caveman full` — Sentence fragments, drop articles (default).
* `/caveman ultra` — Extreme compression, causality arrows (`Cause -> Effect -> Fail`).
* `/caveman off` — Return to standard conversational AI.

### Sub-Commands
* `/caveman commit` — Generate conventional commit message from git diff.
* `/caveman review` — Scan diff for defects without narrative filler.
* `/caveman compress` — Compress raw logs/stack traces.

---

## 📄 License

MIT License. See [LICENSE](./LICENSE) for details.
