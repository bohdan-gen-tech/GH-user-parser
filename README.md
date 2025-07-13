# Get-Honey User Parser from LocalStorage

Tampermonkey userscript to display parsed user data from localStorage on get-honey.ai / .online.

## ✅ Features

- Highlights user ID, email, utmSource, features
- Click to copy user ID
- "Clear site data" button
- Add 1 month subscription (Credentials required)
- Update tokens (Credentials required)
- Delete user
- Draggable, closable overlay panel
- Saves overlay position across reloads

## 🔗 Installation

1. Install [Tampermonkey extension](https://www.tampermonkey.net/).
2. Enable [Developer mode](https://www.tampermonkey.net/faq.php?locale=en#Q209) to use userscripts.
3. [Install](https://raw.githubusercontent.com/bohdan-gen-tech/GH-user-parser/main/get-honey-user-parser.js) "Get-Honey User Parser from LocalStorage" userscript
4. Add Target Domains (@match Rules)
5. Configure API Settings & Credentials:
   - In the same script editor window, scroll down to the // --- CONFIGURATION --- section.
   - Replace the empty configuration object.
   - After pasting, you still need to fill in your admin credentials (email, password) and the API endpoint URLs for your project.
