# HisabPocket

A free, offline-first personal udhaar/payment tracker PWA.

## Deploy from an Android phone
1. Extract this ZIP on your phone.
2. Create a GitHub account/repository and upload the five files in this folder to the repository root.
3. In Cloudflare Dashboard, open Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository. Framework preset: None. Build command: leave empty. Build output directory: `/` (or `.` if the dashboard requests a relative directory).
5. Deploy. Open the generated `pages.dev` URL in Chrome on Android.
6. In Chrome menu, choose **Add to Home screen** or **Install app**.

## Important
- No API, login, cloud database or subscription is used.
- Entries are stored in this browser on this device. They do not sync to another phone.
- Use Backup regularly. Clearing Chrome site data can erase local entries.
- WhatsApp reminders open WhatsApp with a prefilled message; the user must review and send it.
- For privacy, do not use on a shared/unlocked phone without protecting the device.
- This is a personal record-keeping tool, not accounting/tax/banking software.
