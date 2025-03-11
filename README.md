# File-Sorter2

Updated version of File Sorter

## Overview
This Python script automatically categorizes and moves files into organized folders based on their extensions. It provides logging for tracking changes and includes error-handling mechanisms to ensure smooth execution.

## Features
- **Automated File Sorting**: Moves `.csv`, `.png`, and `.txt` files into designated folders.
- **Customizable Rules**: Users can modify the `file_categories` dictionary to support additional file types.
- **Logging Integration**: Tracks created folders and moved files in `file_sorter.log`.
- **Error Handling**: Prevents crashes due to missing directories, permission issues, or inaccessible files.

## How It Works
1. **Define the Target Directory**: Update the `path` variable with the folder where files need to be sorted.
2. **Run the Script**: The script will:
   - Scan the directory for files.
   - Create required folders if they don’t exist.
   - Move files to their respective folders.
   - Log all operations.
3. **Check Logs**: Review `file_sorter.log` for details on moved files and any encountered errors.

## Setup & Usage
1. Install Python (if not already installed).
2. Copy the script into a `.py` file.
3. Modify the `path` variable to match your desired directory.
4. Run the script using:
   ```sh
   python file_sorter.py
   ```
5. Verify organized files in their respective folders.

## Customization
- To add support for more file types, update the `file_categories` dictionary with new extensions and folder names.
- Modify logging settings if needed.

## Troubleshooting
- Ensure the target directory exists.
- Check file permissions if errors occur.
- Review `file_sorter.log` for debugging.

## License
This script is open-source and free to use. Modify and distribute as needed.

