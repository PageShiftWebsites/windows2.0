# windows2.0 🪟

A browser-based Windows 11-inspired desktop experience built with a single self-contained HTML file.

## ✨ Features

* **Boot and login:** Animated boot screen, lock screen, live clock, and login screen.
* **Desktop:** Windows-inspired wallpaper, desktop icons, right-click menus, and draggable icons.
* **Taskbar:** Centered app icons, active-window indicators, system tray, and live date and time.
* **Start menu:** Searchable apps, pinned applications, recommended items, and power controls.
* **Window manager:** Draggable and resizable windows, minimize, maximize, restore, close, and window snapping.
* **Settings:** Light and dark themes, accent colors, wallpaper customization, display brightness, and system information.
* **File Explorer:** Virtual files and folders, file operations, navigation, search, and persistent browser storage.
* **Browser:** Tabs, address bar, navigation controls, and website viewing.
* **Notepad:** Text editing, multiple tabs, search, word wrap, and saving documents.
* **Calculator:** Standard and scientific calculations, keyboard support, and history.
* **Paint:** Drawing tools, colors, adjustable brush size, undo, redo, and saving pictures.
* **Terminal:** Commands including `help`, `dir`, `cd`, `cls`, `echo`, `date`, `time`, `mkdir`, `type`, and `ver`.
* **Task Manager:** Open-window monitoring and the ability to end tasks.
* **Photos:** Picture gallery and image viewing.
* **Clock:** Alarms, timer, and stopwatch.
* **Calendar and Weather:** Calendar interface, events, and sample weather information.
* **Microsoft Store-style app store:** Browse mock application listings and add simulated apps.
* **Media Player:** Play supported audio and video files.
* **Recycle Bin:** Restore deleted files or empty the bin.
* **Widgets:** Weather, news, and to-do list.
* **Keyboard shortcuts:** Win, Alt+F4, Win+D, and Ctrl+Shift+Esc.
* **Easter egg:** Type `bsod` in the Terminal to discover a simulated blue screen.

## 🚀 Getting Started

### Option 1: Run locally

1. Download or clone this repository.
2. Locate `windows2.0.html`.
3. Open the file in Chrome, Edge, or another modern browser.
4. Click the lock screen to unlock the desktop.
5. Sign in using any password, or leave the password empty if supported.

No installation, build tools, external libraries, or server are required.

### Option 2: Host with GitHub Pages

1. Create a GitHub repository.
2. Upload `windows2.0.html` to the repository.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under the build and deployment settings, select **Deploy from a branch**.
6. Choose your main branch and the root folder, then save.
7. Wait for GitHub Pages to publish the site.

You can then open windows2.0 using the published website link.

**Tip:** If you want the website to open directly at the root address, rename `windows2.0.html` to `index.html` before publishing.

## 💾 Saving Files

windows2.0 uses browser local storage to save its virtual file system and certain settings.

* Files are simulated inside the desktop environment.
* Virtual files are not automatically saved to your computer's real folders.
* Clearing browser data may erase locally saved information.
* Data may not automatically synchronize between browsers or devices.

## 🎨 Personalization

Open **Settings → Personalization** to customize supported appearance options, including the theme, accent color, and wallpaper.

## ⌨️ Keyboard Shortcuts

| Shortcut           | Action                   |
| ------------------ | ------------------------ |
| Win                | Open Start               |
| Alt + F4           | Close the focused window |
| Win + D            | Show the desktop         |
| Ctrl + Shift + Esc | Open Task Manager        |

Some shortcuts may be intercepted by your operating system or browser.

## 🛠️ Technology

* HTML5
* CSS3
* Vanilla JavaScript
* Browser local storage
* Canvas API
* Browser media and iframe capabilities

Everything is contained in one HTML file, including the styling and JavaScript.

## ⚠️ Important Limitations

windows2.0 is a desktop simulation, not Microsoft's Windows operating system.

* Some websites prevent iframe embedding.
* Store installations are simulations and do not install native Windows software.
* Weather and news may use sample content.
* Browser-based applications cannot freely access your computer's files or system settings.
* Some functionality depends on browser permissions and compatibility.
* The appearance is inspired by Windows 11 but is not an official Microsoft product.

## 📋 Project Goals

The goal of windows2.0 is to provide a polished, interactive desktop experience that runs directly in a web browser, especially on laptops and Chromebooks.

## 📄 License

Choose a license before distributing or modifying this project publicly. If you intend to publish it as open source, consider adding an appropriate license file.

---

**windows2.0 — Your desktop, in the browser.**
