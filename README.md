# Nexora

**Smart Digital Workspace** - tasks, habits, reminders, expenses, notes, CV builder and more, all in one place.

Built by **Hafsa** as her first app. It runs in any browser, installs like a real app, and works offline.

**Live app:** https://hafsasaeed1280-sys.github.io/nexora/

## What it does

**Plan**
- **Tasks** with priority, due dates, repeating tasks and editing
- **Reminders** with in-app alerts and notifications
- **Calendar** that brings tasks and reminders into one view
- **Focus timer** with daily session stats

**Life**
- **Habit tracker** with streaks and a weekly chart
- **Expense tracker** with a monthly budget, category chart, 6-month trend and a printable PDF report
- **Notes** with pin, colours, tags and search

**Career**
- **Smart Profile** that saves your details once and reuses them
- **CV Builder** with live preview and print to PDF
- **Message Writer** for quick, polished messages

**Everywhere**
- Weekly review of your tasks, habits, spending and focus
- Quick search with `Ctrl + K`
- Sign in with Google and sync across your devices
- Optional PIN lock with auto-lock
- Dark and light themes, many currencies
- Installable app (PWA) that works offline

## Built with

Plain HTML, CSS and JavaScript in a single `index.html`, plus a service worker and web manifest for the installable, offline-ready app. Sign-in and sync use Firebase Authentication and Firestore, with rules so each user can only read and write their own data.

## Privacy

Your data stays in your own browser. If you sign in with Google, a private copy is saved to your own account so it can sync between your devices. The PIN lock is stored only on the device and is meant to keep casual eyes out; it is not bank-grade encryption.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `sw.js` | Service worker (offline support) |
| `manifest.json` | Install settings and icons |
| `icon-*.png`, `apple-touch-icon.png` | App icons |
| `og-image.png` | Preview image when the link is shared |

---

Made with care by Hafsa.
