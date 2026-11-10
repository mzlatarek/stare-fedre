STARE FEDRE V5.10.2 ADMIN RESTORE

ADMIN MODE
1. Edit app-config.js before upload.
2. Keep your working Apps Script URL and SECRET.
3. Replace adminPin:'CHANGE_ME' with your PIN, e.g. adminPin:'2468'.
4. Upload all files.

Viewer mode is the default after every browser/app restart. Viewer can see synced data but write operations require Admin unlock. Admin unlock is session-only on each device.

IMPORTANT: Because GitHub Pages is static, this PIN is UX access control, not cryptographic security. A technically skilled user could inspect app-config.js.
