# SnakeEater

![SnakeEater Screenshot](https://i.imgur.com/12VrYOf.png)

**SnakeEater** is a Python removal tool that can scan your system for Python installations and related files (including virtual environments and pip libraries) and remove them. It also includes a graphical user interface (GUI) with an animated spinning snake that indicates the processing status during the removal operation.

This tool simulates the process of finding and deleting Python installations and related files, making it ideal for users who want to remove Python installations from their systems.

***Note:*** This is a real tool for deleting Python installations, so use it carefully. Ensure you have backups of important files before running it.

---

## Features

- **System Scan**: Scans common Python installation directories and virtual environments for Python-related files.
- **Deep Scan Option**: Offers an option to scan every folder on every drive for Python and pip-related files.
- **GUI with Spinning Snake**: Displays a fun, animated snake that spins when the program is running.
- **Safe Removal Simulation**: Displays which directories will be affected but does not actually delete anything during the simulation.
- **Confirmation Prompts**: Before any action is taken, the user will be prompted to confirm the deletions.
- **No Console Window**: The application runs as a standalone executable with no console window, providing a clean user interface.

---

## Requirements

- Windows OS (Tested on Windows 10 and 11)
- No Python installation required for running the `.exe` (it’s compiled).
  
---

## Installation Instructions

1. **Download the `.exe`** file from the [releases page](#) (or compile it yourself from the source code).
2. Place the `.exe` file in a location where you want to run it from.
3. Double-click to open the application.
   
---

## How It Works

1. **Scan Locations**: The tool checks common Python installation directories, such as:
   - `%LOCALAPPDATA%\Programs\Python`
   - `%PROGRAMFILES%\Python`
   - `%APPDATA%\Python`
   - `~/.virtualenvs`
   - `~/anaconda3`, `~/miniconda3`

2. **Deep Scan Option**: You can opt to scan every folder on every drive by clicking "Yes" when prompted. This will search for any files related to Python and pip, including those in virtual environments.

3. **Simulated Deletion**: Before any deletion is performed, the tool will display a list of detected Python installations and ask for confirmation. If confirmed, it will simulate the removal process by showing which files and folders will be deleted (without actually deleting anything during the simulation).

4. **Actual Deletion**: If you are sure you want to remove Python and related files, the tool will delete the files permanently. This operation is **irreversible**. Always double-check before proceeding.

---

## How to Run the Tool

1. Open the `SnakeEater.exe` file by double-clicking it.
2. The application will show a window with a spinning snake. This means the tool is active.
3. Click on the spinning snake to start the Python removal process.
4. Follow the prompts to either simulate or proceed with the deletion.

---

## Notes

- This tool **removes Python installations**. It should only be used if you are certain that you no longer need Python on your system.
- If you are unsure, **use the simulation mode** to see what will be deleted without actually removing anything from your system.
- This application was developed with Python but has been compiled into a standalone `.exe` file using PyInstaller.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

---

## Disclaimer

**SnakeEater** is intended to be used responsibly. It is a tool for those who wish to remove all traces of Python from their system. Use this tool with caution, and ensure that you have backups of all important files before proceeding with the deletion process.
