# 🔀 50/50 Random Link Redirector

A lightweight, zero-dependency static website that automatically splits incoming traffic equally (50/50) between two destination links on page load.

- **GitHub Repository**: https://github.com/yan-sirui/random-redirect
- **Live Site**: https://yan-sirui.github.io/random-redirect/

---

## ⚙️ How to Change the Links

Open [index.html](file:///Users/jasonyan/Documents/Antigravity/random-redirect/index.html) and update lines 15–16:

```javascript
const LINK_1 = "https://your-first-link.com";
const LINK_2 = "https://your-second-link.com";
```

Then commit and push your changes:
```bash
git add index.html
git commit -m "Update destination links"
git push
```
GitHub Pages will automatically deploy your updates in about 30 seconds!

---

## 🚀 How to Host for Free on GitHub Pages

1. Create a repository on GitHub (or use GitHub CLI).
2. Push this folder's contents to your repository's `main` branch.
3. In your GitHub repo:
   - Go to **Settings** > **Pages** (under "Code and automation").
   - Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)`.
   - Click **Save**.
4. In under a minute, your redirector will be live at `https://<your-username>.github.io/<repo-name>/`!

---

## 🧪 Testing Locally

To test locally in your browser:
```bash
open index.html
```
Or start a local test server:
```bash
python3 -m http.server 8080
```
Open `http://localhost:8080` in your browser (try refreshing a few times to test the 50/50 split).
