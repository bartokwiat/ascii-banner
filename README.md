# ASCII Art Profile Pic Display

A quick little script I put together to show off an ASCII version of my profile picture. It's super simple and runs right in the command prompt.

## How It Works

- The script sets up the console window size, displays the ASCII art from a file called `banner.txt`, and waits for you to press any key to close.
- The ASCII art in `banner.txt` includes some ANSI escape codes to add a splash of color to the display! 🌈
- You can uncomment `chcp 65001 >nul` if you happen to have any UTF-8 characters in your ASCII art.