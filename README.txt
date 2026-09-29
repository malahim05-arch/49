Wedding Photographer v37 REMINDERS
Based on v36. Adds iPhone Web Notifications permission, reminder scheduling while the PWA is active, due-reminder notification on app return, and keeps all v36 data/migration/UI intact.
Important iOS limitation: Safari/PWA does not expose a reliable API for arbitrary future local notifications after the web app is fully terminated. For guaranteed lock-screen alarms, a native iOS app or push backend is required.
