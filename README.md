# QtNotepad
![GitHub Releases](https://img.shields.io/github/downloads/rattle99/QtNotepad/v1.0/total.svg)

<p align="center">
  <img width="609" height="315" src="https://media.giphy.com/media/2YpNAnXlE2tmcZmmDo/giphy.gif">
</p>

___

This is a an effort to try and use Qt5 the c++ gui toolkit. The notepad app is about *50KB* in size and is a standalone [executable](https://github.com/rattle99/QtNotepad/releases) with basic functionalities such as opening, saving, printing and creating new files.

## How to install

### Prerequisites
- Qt5 installed on your machine. You can download it from [here](https://www.qt.io/download).
- A C++ compiler like `g++`.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/rattle99/QtNotepad.git
   cd QtNotepad/QtNotepad
   ```
2. Open the project in Qt Creator or use the command line:
   ```sh
   qmake QtNotepad.pro
   make
   ```
3. Run the application:
   ```sh
   ./QtNotepad
   ```

## How to use

### Basic Functionalities
- **New File**: Click on `File` > `New` to create a new document.
- **Open File**: Click on `File` > `Open` to open an existing document.
- **Save File**: Click on `File` > `Save As` to save the current document.
- **Print File**: Click on `File` > `Print` to print the current document.
- **Exit Application**: Click on `File` > `Exit` to close the application.
- **Copy Text**: Click on `Edit` > `Copy` to copy the selected text.
- **Paste Text**: Click on `Edit` > `Paste` to paste the copied text.
- **Cut Text**: Click on `Edit` > `Cut` to cut the selected text.
- **Undo Action**: Click on `Edit` > `Undo` to undo the last action.
- **Redo Action**: Click on `Edit` > `Redo` to redo the last undone action.

## Licensing

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>