## VS Code Language Extension for COSY INFINITY

Syntax highlighting and editor configuration for COSYScript (`.fox`) files.

Written by Ao Liu, [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/).
Contact: [liuao@shanghaitech.edu.cn](mailto:liuao@shanghaitech.edu.cn)

COSY INFINITY is an arbitrary-order beam-dynamics simulation and analysis code. It supports accelerator lattices, spectrographs, beamlines, electron microscopes, and other charged-particle optical systems. More information is available from [Beam Physics and Technology](https://www.bmtdynamics.org/cosy/).

### Features

- `.fox` file association and COSY language mode
- COSY keywords, declarations, intrinsics, beam-physics procedures, operators, and numeric literals
- Single-quoted strings with doubled-quote escapes
- Nested `{ ... }` block comments
- Bracket matching, automatic closing, and selection surrounding

### Install from a VSIX

1. Download the latest `cosy-*.vsix` release artifact.
2. In VS Code, run **Extensions: Install from VSIX…** from the Command Palette.
3. Open a `.fox` file and confirm the language indicator shows **COSY**.

The extension is declarative and contains no executable extension-host code.
