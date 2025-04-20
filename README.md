# 🧠 localgptlite

A lightweight, no-dependency, locally-hosted chat UI for OpenAI's GPT models.  
Built with vanilla HTML, CSS, and JS. No React. No frameworks. No Vercel. No bloat.

## 🚀 Why This Exists

Because you don’t need seventeen npm packages, serverless lambdas, and a full-blown frontend framework to send a string 
to an API and display a response. I just wanted to use GPT 4.1 but I quickly discovered that

Most GPT UI clones are either:
- Broken
- Hard code the available models and haven't updated
- Over-engineered messes
- Tied to some cloud service

**localgptlite** is 500 lines of HTML, CSS, and JS. It meets all my needs for now and took almost no time at all to 
"develop" (ChatGPT 4o built this I just complained until it was right).

## ✨ Features

- 🧠 Multi-chat memory (stored in `localStorage`)
- 🧾 Usage stats (token count + cost estimate)
- 🎯 Syntax-highlighted markdown rendering with `highlight.js`
- 📋 Copy buttons on every code block
- ↩️ Press `Enter` to send, `Shift+Enter` for newline
- ⚙️ Toggleable settings drawer for API key + model
- 🪶 Zero dependencies (outside of two CDN scripts)
- 🔐 Works entirely in the browser — your key stays local
- 💻 Looks great in dark mode, works offline once cached

## 🛠 Setup

1. Clone the repo
2. Open `chat.html` in your browser
3. Paste your OpenAI API key
4. Start typing

That’s it.

## 🧩 Tech Stack

- **HTML/CSS/JS** like it’s 2005 and the web just works
- [`marked`](https://github.com/markedjs/marked) for Markdown parsing
- [`highlight.js`](https://highlightjs.org/) for code syntax highlighting

No build step. No bundler. No tailwind. No node_modules. No SSR. 

## 🔒 Security

It isn't secure, it stores the API key in local storage. If you want it to be then make it so. It's 400 lines of HTML 
and JS.

---

<img width="1728" alt="image" src="https://github.com/user-attachments/assets/29015c6e-bb3f-422a-b777-9c50ba1fdfb8" />


> Made with spite, speed, and a healthy disrespect for unnecessary complexity.
