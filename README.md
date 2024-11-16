# Limon+ Tools

Welcome to **Limon+ Tools**, a collection of lightweight and functional web applications designed to enhance productivity and security. This repository includes two main tools: a **Notepad** and an **Authenticator**.

## Features

### Notepad
- A lightweight, online text editor for quick note-taking.
- Features:
  - Save text to cookies for persistence across sessions.
  - Download notes as `.txt` files.
  - Clear the editor with a confirmation prompt.

### Authenticator
- Generate **TOTP (Time-Based One-Time Passwords)** for secure multi-factor authentication (MFA).
- Features:
  - Add, view, and manage secret keys.
  - Generate and refresh TOTP codes every 30 seconds.
  - Delete secret keys with a confirmation prompt.

### Progressive Web App (PWA)
- Installable on desktop and mobile devices.
- Works offline thanks to service worker caching.

## Live Website
Visit the live version of the project here: [Limon+ Tools](https://limondasplus.github.io)

## How to Use

### Notepad
1. Open the [Notepad](https://limondasplus.github.io/notepad.html) page.
2. Type your notes in the editor.
3. Use the **Save** button to save your notes to cookies.
4. Use the **Download** button to download your notes as a `.txt` file.
5. Use the **Clear** button to clear the text editor (requires confirmation).

### Authenticator
1. Open the [Authenticator](https://limondasplus.github.io/auth.html) page.
2. Add a service name and its secret key to generate TOTP codes.
3. View TOTP codes that refresh automatically every 30 seconds.
4. Delete a service's secret key if no longer needed.

## Installation (Optional for Local Use)
1. Clone the repository:
   ```bash
   git clone https://github.com/limondasplus/limondasplus.github.io.git
