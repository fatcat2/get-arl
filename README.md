# Get Deezer ARL Cookie

A simple tool to extract your Deezer ARL cookie value using a bookmarklet.

## 🚀 Quick Start

1. Open `index.html` in your browser
2. Drag the "Get Deezer ARL" button to your bookmarks bar
3. Go to [deezer.com](https://www.deezer.com) and log in
4. Click the bookmarklet in your bookmarks bar
5. Copy your ARL value!

## 📖 Why a Bookmarklet?

**Pure HTML cannot access cookies from other domains** due to browser security policies (Same-Origin Policy).

A bookmarklet is a JavaScript snippet that:
- Runs **on** the Deezer page itself (so it has access to cookies)
- Requires no installation or browser extensions
- Works on all modern browsers
- Can be distributed as a simple HTML file

## 🔒 Security Note

Your ARL cookie is sensitive - it provides access to your Deezer account. Never share it with anyone you don't trust.

## 🛠️ Alternative Methods

### Manual Method (Developer Tools)
1. Go to deezer.com and log in
2. Press `F12` to open Developer Tools
3. Go to **Application** (Chrome) or **Storage** (Firefox) tab
4. Navigate to **Cookies** → **https://www.deezer.com**
5. Find the cookie named `arl` and copy its value

### Browser Extension
For a more permanent solution, you could create a browser extension with cookie permissions.

## 📝 License

MIT
