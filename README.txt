HELPHUB - Community Help & Volunteer Platform

Files:
- helphub.html : complete one-file HTML/CSS/JavaScript Firebase project

Firebase setup:
1. Enable Authentication > Sign-in method > Email/Password.
2. Create/enable Realtime Database.
3. For initial college testing, database rules can be:
{
  "rules": {
    ".read": "auth != null",
    ".write": "auth != null"
  }
}
4. Register an account, copy its UID, and change /users/UID/role to "admin" in Realtime Database.
5. Open helphub.html using a local server or deploy it to GitHub Pages.

The project contains Help mode, Volunteer mode, admin management, realtime requests/offers and realtime chat.
