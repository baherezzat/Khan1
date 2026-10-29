# Upload this website with all images

The `assets` folder must be uploaded together with `index.html`, `style.css`, and `script.js`. Do not use GitHub's browser file-upload page for this package because the website contains more than 100 files.

## Recommended: GitHub Desktop

1. Install and open GitHub Desktop.
2. Choose **File → Clone repository → URL**.
3. Enter `https://github.com/baherezzat/Khan-al-harir` and clone it.
4. Open the cloned repository folder on your computer.
5. Copy everything from this folder into the cloned repository. Confirm that the cloned repository now contains the complete `assets` folder.
6. In GitHub Desktop, enter the summary `Add all website images`, select **Commit to main**, then select **Push origin**.
7. Vercel will automatically create a new deployment. Refresh the site after that deployment shows **Ready**.

## Required repository structure

```text
Khan-al-harir/
├── assets/
│   ├── menu/
│   ├── khan-logo.webp
│   └── all other website images
├── index.html
├── style.css
├── script.js
└── CREDITS.md
```
