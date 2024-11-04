# MinGW 32-bit Compiler

This repository contains a backup of the **MinGW 32-bit compiler**. Since the original files are often hard to find and unreliable to download, you can easily get a working version here.

## About
MinGW is a minimalist GNU for Windows, providing a compiler and various development tools. This repository is a solution for those who need the **32-bit version of MinGW** and are unable to download it from the usual sources like SourceForge.

## How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/mingw-32bit](https://github.com/Abdullah-Mian/MinGW-32bit.git)
   ```

2. After cloning, locate the `bin` folder inside the MinGW directory.

3. **Add the `bin` folder path to your system environment variables** to make the MinGW tools accessible from any command line.

   ### Adding the Path in Windows:
   - Go to **Control Panel** → **System** → **Advanced system settings**.
   - Click on **Environment Variables**.
   - Under **System variables**, find and select the `Path` variable, then click **Edit**.
   - Add the full path of the MinGW `bin` folder (e.g., `C:\path\to\mingw\bin`) to the list.
   - Click **OK** to save your changes.

4. Verify the installation by opening a new terminal and typing:
   ```bash
   gcc -v
   ```
   You should see version information confirming that GCC (GNU Compiler Collection) is installed.

## Notes
- This repository only contains the **32-bit version of MinGW**.
- It’s recommended to use this version if you’re facing trouble downloading MinGW directly.

