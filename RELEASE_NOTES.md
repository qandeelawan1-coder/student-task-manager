v1.0.1 (Hotfix)

Release Date: 23 November 2026

Bug Fixes
Fixed the login button not responding or not displaying correctly on mobile devices (button now full width with a larger touch area on small screens).
Known Issues
Same as v1.0.0 (see below).
v1.0.0 (First Stable Release)

Release Date: 23 November 2026

New Features
User signup and login
Add tasks
Delete tasks
Mark tasks as complete
Task counter ("X of Y done")
Light and dark mode support
Bug Fixes
Fixed empty-title tasks being saved (validation added)
Fixed session loss on page refresh
Fixed tasks being rendered as raw HTML (input is now treated as plain text)
Known Issues
Data is stored in the browser (localStorage), so accounts and tasks do not sync between devices
Passwords use a simple hash, which is suitable for a demo only and is not real security
No password reset option
Tasks cannot be edited after creation
Layout on very small mobile screens may need improvement (addressed in v1.0.1)