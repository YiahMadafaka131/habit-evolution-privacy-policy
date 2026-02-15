# Privacy Policy Repository

This folder contains the Privacy Policy for Habit Evolution, styled to match the application.

## How to Publish to GitHub Pages

1.  **Create a new repository on GitHub:**
    *   Name it `privacy-policy-repo` (or whatever you prefer, but update the link in the app if you change it).
    *   **Important:** Do *not* initialize with README, license, or .gitignore (keep it empty).

2.  **Push this code:**
    Open a terminal in this folder (`c:\Users\Alexis\.gemini\antigravity\scratch\habit-evolution\privacy-policy-repo`) and run:
    
    ```bash
    git remote add origin https://github.com/YiahMadafaka131/privacy-policy-repo.git
    git branch -M main
    git push -u origin main
    ```

3.  **Enable GitHub Pages:**
    *   Go to your new repository on GitHub.
    *   Go to **Settings** > **Pages**.
    *   Under "Build and deployment", select **Source** as "Deploy from a branch".
    *   Select **main** branch and **/(root)** folder.
    *   Click **Save**.

4.  **Verify Link:**
    The privacy policy should be live at: `https://YiahMadafaka131.github.io/privacy-policy-repo/`
