# Smart File Organizer

**Smart File Organizer** is a simple Python script that automatically sorts files in a given folder based on their actual content – not just the file extension.

## Features
- Detects file type using MIME type (e.g., PDF, image, text, spreadsheet).
- Creates subfolders for:
  - Images
  - PDFs
  - Text_Files
  - Spreadsheets (Excel/CSV)
  - Other (miscellaneous files)
- Moves files into the appropriate folders.
- Works on Windows, macOS, and Linux.

## Usage

```bash
python smart_file_organizer.py /path/to/your/folder
