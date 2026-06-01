<div align="center">
  # Web-Deck Releases
  
  **Download the latest compiled versions of Web-Deck for macOS, Windows, and Linux.**
</div>

---

## 📥 Download

Grab the latest native installer for your operating system from the [Releases Page](https://github.com/webdeck-app/Launch-Deck-Releases/releases).

- **Mac (Apple Silicon):** `Web-Deck-*-arm64-mac.zip`
- **Mac (Intel):** `Web-Deck-*-mac.zip`
- **Windows:** `web-deck-*-setup.exe`
- **Linux:** `web-deck-*-linux.AppImage`

---

## ⚠️ Important Note for Mac Users

Because Web-Deck is not currently signed with a paid Apple Developer certificate, macOS Gatekeeper may flag the app as **"damaged"** when you try to open it for the first time.

**To bypass this security check:**
1. Move the extracted **Web-Deck.app** to your `/Applications` folder.
2. Open your **Terminal** application and run this exact command to clear the quarantine flag:
   ```bash
   xattr -cr /Applications/Web-Deck.app
   ```
3. You can now double-click and open Web-Deck normally!
