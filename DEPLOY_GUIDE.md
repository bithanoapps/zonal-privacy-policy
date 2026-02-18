# How to Deploy to GitHub Pages

1.  **Create a GitHub Repository**:
    *   Go to [GitHub.com](https://github.com) and create a new repository (e.g., `zonal-privacy-policy`).
    *   Make sure it is **Public**.

2.  **Push Code to GitHub**:
    *   Initialize git in your project folder if you haven't already:
        ```bash 
        git init
        git add .
        git commit -m "Initial commit"
        ```
    *   Link your local repository to the remote GitHub repository:
        ```bash
        git remote add origin https://github.com/YOUR_USERNAME/zonal-privacy-policy.git
        git branch -M main
        git push -u origin main
        ```

3.  **Enable GitHub Pages**:
    *   Go to your repository **Settings** tab.
    *   Scroll down to the **Pages** section (or click "Pages" in the left sidebar).
    *   Under **Source**, select `Deploy from a branch`.
    *   Under **Branch**, select `main` and `/ (root)`.
    *   Click **Save**.

4.  **Wait for Deployment**:
    *   GitHub will generate a link (usually `https://YOUR_USERNAME.github.io/zonal-privacy-policy/`).
    *   It might take a minute or two to go live. Refresh the page to see your site!
