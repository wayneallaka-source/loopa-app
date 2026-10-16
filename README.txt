LOOPA PWA starter (free prototype)
===================================

Included:
- Responsive premium-dark web app shell
- Local demo posts, chats, channels, and personal goals
- Demo chat lock prompt (passcode 2468; NOT secure encryption)
- No AI integration
- PWA manifest and service worker for installability/offline shell

Important limitations:
- This is NOT a real online social network yet.
- Local demo messages/posts are stored in the browser on one device only.
- Messages are NOT delivered to friends, are NOT end-to-end encrypted, and should not contain sensitive information.
- A local passcode prompt is a demonstration only, not secure locked-chat protection.
- No real accounts, backend, push notifications, media uploads, or calls.
- PWA installation requires the project to be hosted over HTTPS. A static host can serve the front end for free, but real multi-user messaging requires backend setup and testing.

To preview:
Open index.html in a modern browser. Service-worker/offline install features generally require HTTPS or localhost.

Next engineering stage:
Connect authentication, database/realtime messaging, storage, and audited end-to-end encryption. Keep AI out of messaging entirely, as requested.
