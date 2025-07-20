# Subtle Blue Accent Theme

> A theme for VS Code, subtle background with blue accent.

## Usage for AI‑powered code editors

**This incredibly beautiful theme may encounter an issue where it doesn’t get listed in the marketplaces of newly released AI‑powered code editors (Windsurf, Kiro, etc.), so please use the manual download guide we’ve added at the bottom and get back to life.** [🔽 Go Manual Installation](#manual-installation-with-vsix)

## Screenshots

![Screenshot 1](images/subtle-blue-1.png)
![Screenshot 2](images/subtle-blue-2.png)
![Screenshot 3](images/subtle-blue-3.png)

## Installation with Marketplace

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Launch Visual Studio Code
3. Open the **Extensions** view (⇧⌘X on Mac or Ctrl+Shift+X on Windows/Linux)
4. Search for `subtle-blue`
5. Click **Install**
6. Click **Reload** if prompted
7. Open **File** > **Preferences** > **Color Theme** (or ⇧⌘P / Ctrl+Shift+P, then type **Color Theme**)
8. Select **Subtle Blue**

## Manual Installation with VSIX

1. **Clone the repo and go to the dist directory**

   ```bash
   git clone https://github.com/BlanchDev/vscode-Theme-Subtle-Blue.git
   cd vscode-Theme-Subtle-Blue
   cd dist
   ```

2. **Install the VSIX package**

   - The file `subtle-blue-1.0.7.vsix` is already in the `dist/` folder, so you can skip building it.

   _Examples with Windsurf._

   For custom user profile.

   ```bash
   windsurf --profile "your_profile_name" --install-extension subtle-blue-1.0.7.vsix
   ```

   For default user profile.

   ```bash
   windsurf --install-extension subtle-blue-1.0.7.vsix
   ```

3. **Select the theme**

   ```bash
   Ctrl+Shift+P  # Then "Preferences: Color Theme"
   Subtle Blue
   ```

   or reload and select

   ```bash
   Ctrl+Shift+P  # Then "Developer: Reload Window"
   Ctrl+Shift+P  # Then "Preferences: Color Theme"
   ```

> Enjoy the soft subtle vibes! 🌸
