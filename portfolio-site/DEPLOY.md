# Deployment Instructions for Portfolio Website on GitHub Pages

## Prerequisites
- You have a GitHub account (https://github.com/rolexsairoshan)
- You have created a GitHub repository to host your portfolio website.
  - For user/organization site, name the repo as `rolexsairoshan.github.io`
  - For project site, any repo name is fine.

## Steps to Deploy

1. Open a terminal and navigate to the `portfolio-site` directory:
   ```
   cd path/to/portfolio-site
   ```

2. Initialize git (if not already initialized):
   ```
   git init
   ```

3. Add your GitHub repository as remote origin:
   ```
   git remote add origin https://github.com/rolexsairoshan/your-repo-name.git
   ```

4. Add all files and commit:
   ```
   git add .
   git commit -m "Initial commit - add portfolio website"
   ```

5. Push to GitHub:
   ```
   git branch -M main
   git push -u origin main
   ```

6. Enable GitHub Pages in your repository settings:
   - Go to your GitHub repository page.
   - Click on **Settings** > **Pages**.
   - Under **Source**, select the branch `main` and folder `/ (root)`.
   - Save.

7. Your site will be published at:
   - For user site: `https://rolexsairoshan.github.io/`
   - For project site: `https://rolexsairoshan.github.io/your-repo-name/`

## Notes
- Make sure your `index.html` is in the root of the repository or the selected folder.
- You can update your portfolio by committing and pushing changes to the repository.

If you want, I can help you automate these git commands.
