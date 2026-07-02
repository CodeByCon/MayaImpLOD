# Ultimate LOD & Impostor Creation Tool for Maya — v1.0

Free, open-source LOD generator and billboard baker for Maya. No paid plugins, no admin rights needed — runs entirely from the Script Editor.

Made because Maya's native LOD tools lack batch automation, paid enterprise optimization suites cost thousands, and that's annoying when you just need game-ready assets.

---

## Install

1. Open Maya 2026 and go to the bottom middle of your screen where it says "MEL" and a text input box on the right.
2. Copy the code below and paste it in.
3. Press enter.

```mel
python("import urllib.request as r; exec(compile(r.urlopen('https://raw.githubusercontent.com/CodeByCon/MayaImpLOD/main/implod_studio.py').read(),'<implod>','exec'))");
```

Runs the latest version straight from GitHub every time — no files to manage. Save it as a shelf button for one-click access.

Zero external dependencies. Texture grid compilation, matrix math, and geometry handling are driven entirely via native Maya 2026 Python 3.11 APIs. No admin rights required.

---

<details>
<summary><b>Features</b></summary>

//TODO

</details>

---

## Credits

| | |
|---|---|
| Connor Henry | Main Developer |
| Claude / Anthropic | Architecture & Automation Logic |

---

## License
This project, MayaImpLOD, is licensed under the Apache License 2.0.

You are free to use, modify, and distribute this software, but you must:
- Credit Connor Henry as the original author
- Include a link to this license
- State if changes were made

For full terms, see the LICENSE file on the repository.

### Academic or Media Use
If you use MayaImpLOD in research, a publication, or media, please cite:
> Henry, C. (2026). MayaImpLOD: An Automated LOD and Impostor Maker for Autodesk Maya.
