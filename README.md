# AGAM TV — IPTV Player

AGAM TV is a modern, cross-platform IPTV application that streams live TV channels from JioTV. No external player or configuration required — just sign in with your Jio number and start watching.

## Features

- **Live TV Streaming** — Watch 500+ live TV channels across languages (Tamil, English, Hindi, Telugu, Malayalam, Kannada, Bengali, and more)
- **Language-Based Categories** — Channels organised by language. Favourites, Tamil, English, Hindi, Telugu pinned first for quick access
- **Search** — Find any channel instantly by name
- **Favourites** — Save your frequently watched channels for quick access
- **Built-in Player** — No external apps needed. Streams play directly with hardware-accelerated video playback
- **Cross-Platform** — Available for Android and Linux (AppImage)
- **JioTV Integration** — Secure OTP login with automatic token refresh. No manual configuration or playlist files needed

## Downloads

Download the latest release from the [Releases page](https://github.com/karmedia/agamtv-releases/releases).

| Android (.apk) | Linux (.AppImage) |
|----------------|-------------------|
| Install directly on your phone or Android TV | Download, make executable, and run:<br>`chmod +x AgamTV-*.AppImage`<br>`./AgamTV-*.AppImage` |

## Usage

1. Install & launch the app
2. Sign in with your Jio phone number:
   - Enter your 10-digit Jio mobile number
   - Enter the OTP sent to your phone
   - You're signed in — no password needed
3. Browse channels by language tab
4. Tap any channel to start watching instantly
5. Use the heart icon to save favourites

Your session is maintained automatically. No repeated logins.

## Notes

- Requires an active Jio prepaid/postpaid connection with JioTV access
- Internet connection required for streaming (WiFi or mobile data)
- Some premium channels may require an additional subscription to watch
- Android TV remote works with directional navigation
- For Linux: AppImage runs on most distributions. GTK3 and libmpv are required (installable via your package manager)
