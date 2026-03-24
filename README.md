# 🔥 Promptstitute
A powerful Chrome extension that lets you instantly insert reusable prompt templates into AI chat editors across ChatGPT, Claude, Gemini, and Perplexity.

Promptstitute helps you work faster by turning your best prompts into reusable snippets — complete with placeholder navigation, multi‑site support, and a clean dropdown UI triggered directly inside the editor.

---

## ✨ Features

### 🧩 Multi‑Site Support
Promptstitute works seamlessly across:
- ChatGPT (chat.openai.com, chatgpt.com)
- Claude (claude.ai)
- Gemini (gemini.google.com)
- Perplexity (perplexity.ai)

Each site uses a dedicated adapter for reliable insertion.

### ⚡ Trigger‑Based Snippet Lookup
Type:
- `.template:`  
- or `/:`

…and a dropdown instantly appears with matching snippets.

Supports:
- Real‑time filtering  
- Keyboard navigation  
- Enter to insert  
- Escape to close  

### 📝 Snippet Insertion Engine
Robust insertion across multiple editor types:
- ProseMirror editors (ChatGPT, Claude)
- DOM‑based editors (Gemini, Perplexity)

Ensures:
- Only the trigger is replaced  
- Cursor position is preserved  
- No full‑text overwrites  

### 🔧 Placeholder Navigation
Use `{variable}` tokens inside snippets.

After insertion:
- **Tab** → jump to next placeholder  
- **Shift+Tab** → jump backwards  
- Placeholder disappears when you type  

### 📚 Snippet Management
Full CRUD interface in the Options page:
- Create  
- Edit  
- Delete  
- Import / Export JSON  
- Conflict detection on import  
- Auto‑generated stable snippet IDs  

### 🔄 Cross‑Context Editing
Click the ✏️ icon in the dropdown to:
- Open the Options page  
- Auto‑scroll to the snippet  
- Open it in the editor modal  

### 🛠️ Diagnostics & Debug Tools
- **Alt+Shift+D** → toggle debug mode  
- **Alt+Shift+V** → ProseMirror view diagnostics  
- Handles dynamic DOM changes  
- Detects invalid extension contexts  

---

## 🚀 Installation

### From the Chrome Web Store
**[Install Promptstitute →](https://Promptstitutes.vercel.app/)**  

### From Source (Developer Mode)
1. Clone this repo  
2. Go to `chrome://extensions`  
3. Enable **Developer Mode**  
4. Click **Load unpacked**  
5. Select the project folder  

---

## 🎯 How to Use

### 1. Open ChatGPT, Claude, Gemini, or Perplexity  

### 2. Type a trigger: .template: or /:

### 3. Select a snippet  
Use arrow keys or click.

### 4. Insert with Enter  
Placeholders become active.

### 5. Navigate placeholders  
- Tab → next  
- Shift+Tab → previous  

---

## 🧩 Import / Export Snippets

### Export
Options → Export → Downloads a JSON file.

### Import
Options → Import → Preview → Confirm.

Conflicts (same name) will prompt before overwriting.

---

## 🐞 Reporting Bugs

Please use the **Bug Report** template:  
[Bug Report Template](https://github.com/GunderwoodG/Promptstitute/blob/main/.github/ISSUE_TEMPLATE/bug_report.md)

Include:
- OS  
- Chrome version  
- Site where it happened  
- Extension version  
- Steps to reproduce  
- Screenshots or video  
- Whether debug mode was enabled  

---

## 💡 Requesting Features

Use the **Feature Request** template:  
[Feature Request Features](https://github.com/GunderwoodG/Promptstitute/blob/main/.github/ISSUE_TEMPLATE/feature_request.md)

Tell us:
- The problem it solves  
- The feature you want  
- Where it applies (ChatGPT, Claude, Gemini, Perplexity, Options page)  
- Any examples or mockups  

---

## 🛠️ Contributing

Contributions are welcome!  
See the full guide here:

**[CONTRIBUTING.md](./CONTRIBUTING.md)**

---

## 📄 Privacy

Promptstitute does **not** collect personal data.  
All snippets are stored locally using `chrome.storage.sync`.

Full policy:  
[Policy Page](https://Promptstitutes.vercel.app/privacy)

---

## ❤️ Support the Project

If you find Promptstitute useful, consider supporting development:

- Patreon  
- Venmo  
- BuyMeACoffee  

(Links coming soon.)

---

## 📅 Roadmap

### Near‑Term
- Snippet categories + search  
- Inline preview in dropdown  
- Slash commands (`/blog`, `/pitch`, etc.)  
- Live preview in snippet editor  

### Long‑Term
- Interactive placeholder forms  
- Snippet packs (installable libraries)  
- Cloud sync + user accounts  
- Universal adapter for more AI platforms  

---

## 🧑‍💻 License

MIT License — free to use, modify, and distribute.

---

## 🔥 Built for creators, writers, developers, and anyone who works with AI.

Promptstitute helps you work faster, stay organized, and turn your best prompts into reusable tools.
