# 🎓 Student-Finance-Tracker 💰

This is a course requirement for CS 191/192 Software Engineering Courses of the Department of Computer Science, College of Engineering, University of the Philippines, Diliman, under the guidance of Ma. Rowena C. Solamo for A.Y. 2023-2024.

## 🚀 The Project

**Student Finances Tracker** makes managing money simple and intuitive for students. Track and record your transactions easily while watching your wallet update in real time. Enjoy visual insights through graphs 📊, reports 📈, and calendars 📅 to understand your spending habits and make smarter financial decisions. With a clean and user-friendly interface, this app empowers students to stay organized and financially savvy.

Built with [SvelteKit], [Node.js], and [firebase], and powered by [pnpm] as the package manager, it can be deployed both as a web app and a mobile app using [Capacitor.js].

[Node.js]: https://nodejs.org/  
[SvelteKit]: https://kit.svelte.dev/  
[PostgreSQL]: https://www.postgresql.org/  
[pnpm]: https://pnpm.io/  
[capacitor.js]: https://capacitorjs.com/  

## 👩‍💻 Development Team

- Narte, Jeric (lead)
- Jafri, Ali Mahmood  
- Javier, Timothy 
- Santos, Vincent Marcel
  
## ⚙️ Using the Codebase

Before running the project, make sure you have **Node.js**, **PostgreSQL**, **pnpm**, and either [Android Studio] or [Xcode] installed on your system.

[Android Studio]: https://developer.android.com  
[Xcode]: https://developer.apple.com/xcode/

### Web deployment

```bash
# Install project dependencies.
pnpm install
# Sync auto-generated files from SvelteKit.
pnpm sync
# Start development server with live reloading and hot module replacement.
pnpm dev
# Compile production build with optimizations.
pnpm build
# Start production preview server.
pnpm prev
```

### Mobile deployment

```bash
# build android package
pnpm build:android
# build ios package
pnpm build:ios
# open application in android studio
pnpm prev:android
# open application in xcode
pnpm prev:ios
```

### Linting and Formatting

```bash
# Check code format issues
pnpm fmt
# Fix code format issues
pnpm fmt:fix
# Check all Lints and format
pnpm check
```
