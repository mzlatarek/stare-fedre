STARE FEDRE V5.8

CENTRAL SYNC SETUP
1. Open app-config.js in a text editor.
2. Replace PASTE_APPS_SCRIPT_EXEC_URL_HERE with the Apps Script URL ending in /exec.
3. Replace PASTE_THE_SAME_SECRET_HERE with the SECRET from Code.gs.
4. Upload all files to the GitHub Pages repository root.
5. Every device receives the same connection automatically.

IMPORTANT
The repository must be private if you want the secret hidden, but GitHub Pages from a private repository depends on the GitHub plan. In a public static site, any frontend secret can be inspected. Treat this key as a simple write guard, not strong authentication.

MOBILE CHANGES
- Compact sticky header
- 2x2 KPI cards
- Bottom navigation
- Single-column calendar and forms
- Mobile bottom-sheet dialogs
- Horizontal banner statistics
- Automatic cloud check on startup
