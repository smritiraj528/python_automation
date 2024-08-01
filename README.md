# Desktop Organizer

Desktop Organizer is a Python automation script that organizes files on your desktop by automatically moving files into designated folders based on their file types. This helps keep your desktop clean and makes it easier to find and manage your files.

## Features

- Automatically moves files to designated folders based on their file extensions.
- Supports common file types like documents, images, videos, music, and more.
- Easily configurable to add new file types or change the destination folders.
- Runs periodically to keep your desktop organized at all times.

## Requirements

- Python 3.x
- `os` module (comes with Python standard library)
- 'watchdog' mdoule
- `shutil` module (comes with Python standard library)
- `time` module (comes with Python standard library)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/desktop-organizer.git
    cd desktop-organizer
    ```

2. **Create the necessary folders on your desktop:**
    Create folders for each file type you want to organize (e.g., Documents, Images, Videos, Music).

3. **Edit the script to match your folder paths:**
    Update the folder paths in the `folders` dictionary in `desktop_organizer.py` to match the folders you created on your desktop.

## Usage

1. **Run the script:**
    ```bash
    python desktop_organizer.py
    ```

2. **Automate the script:**
    You can set up a task scheduler to run the script periodically. On Windows, use Task Scheduler; on macOS, use Automator or cron jobs.


    'Videos': ['.mp4', '.mov', '.avi', '.mkv'],
    'Music': ['.mp3', '.wav', '.aac', '.flac'],
    'Archives': ['.zip', '.rar', '.7z'],
    'Scripts': ['.py', '.js', '.sh'],
}
