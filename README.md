# GitHub Pages GA4 Redirect

This is a static redirect page that sends analytics to Google Analytics 4 (Measurement ID **G-5Q34Z8YTVL**) and then forwards the visitor to the Drive file.

## Deployment

1. Upload this folder to a **public** GitHub repository (e.g., `drive-redirect`).
2. Enable **GitHub Pages** → Settings → Pages → Deploy from branch → `main` → `/ (root)`.
3. Your tracking link will be:

   ```
   https://hellospaghettibot.github.io/drive-redirect/
   ```

4. In Google Analytics 4, open **Realtime** or **Events** → you’ll see a `redirect` event with full geography, device, and referrer info.
