# XXMI Launcher (modified)
Modified for my own purpose

### What changed?
- Wuthering Waves -> General Settings, option to not configure Engine.ini

### How to use this?
1. Get the release zip file, it's portable version.
2. Use it as usual.

### How did I build it? (Personal Notes)
1. With Python Nuitka
2. `python -m nuitka .\src\xxmi_launcher\app.py --standalone --enable-plugin=tk-inter --windows-company-name="XXMI" --windows-product-name="XXMI Launcher" --windows-file-version="9.9.9" --windows-product-version="9.9.9" --windows-uac-admin --windows-console-mode=disable`
3. Output in `app.dist` folder, rename this folder to be `Bin`.
4. Get original XXMI Launcher portable version, inside original `Bin` folder, copy-paste `Bin\tcl\tkhtml` to modified `Bin` folder.
5. Delete original `Bin` folder, replace with modified `Bin` folder.
