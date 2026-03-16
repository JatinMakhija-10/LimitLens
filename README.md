# LimitLens 🛰️

A sleek, sci-fi-themed, client-side web application designed to track AI application token limits and reset timers across multiple accounts (specifically for Claude and Gemini).

## Features

- **Multi-Account Tracking:** Add all your different accounts in one place.
- **Dual Timers:** Track both Claude and Gemini on a single account profile independently.
- **Custom Reset Windows:** Input precise reset timers specifying exactly how many Days, Hours, and Minutes are left.
- **Immediate 'Hit Limit' Reset:** A single click on "Hit Limit" immediately resets all the timers for that account to the current time plus the specified wait window.
- **Auto-Filtering:** Accounts where timers are complete automatically filter into a "Limit Renewed" tab.
- **Data Privacy:** Everything is stored exclusively on your device using `localStorage`. No data leaves your machine.
- **Cyber-Aesthetic UI:** Beautiful glassmorphism cards, glowing status dots, circular SVG progress rings, and a dynamic canvas-based starfield background.

## Getting Started

1. Clone or download the repository.
2. Open `index.html` directly in your favorite modern web browser.
3. Tap the **`+`** button to create a new tracking card.
4. Input your Account name, select the Models (Claude, Gemini, or both), and input the required reset windows.

## Technologies Used

- **React 18** (Loaded via CDN)
- **Babel Standalone** (For inline JSX transpilation)
- **Vanilla CSS** (No external style frameworks, utilizing glassmorphism and keyframe animations)
- **HTML5 Canvas** (For the interactive starfield effect)

## License

This project is open-source. Feel free to use and modify it.
