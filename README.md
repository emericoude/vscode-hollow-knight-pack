# README

This is an extension pack (set of extensions) made for anyone to be able to use my Hollow Knight Theme to its fullest!

**IF THIS OR ANY FILE I ASK YOU TO EDIT IS EXTREMELY LONG AND LAGGY, DO ALT+Z, it should help (somewhat).**

**INSTRUCTIONS** || Uninstall instruction at the end
1. In your json settings (CTRL+SHIFT+P -> Preferences: Open Setting (JSON)), copy paste the settings below

    "vscode_custom_css.imports": [
        "file:///C:/Users/[INSERT-USERNAME-HERE]/.vscode/extensions/robbowen.synthwave-vscode-0.1.11/synthwave84.css",
    ],

    //OPTIONAL
    "editor.glyphMargin": false,
    "editor.folding": false,
    "editor.lineNumbers": "on",
    "editor.showFoldingControls": "mouseover",
    "editor.lineDecorationsWidth": 0, // undocumented
    "editor.lineNumbersMinChars": 4, // undocumented
    "editor.cursorBlinking": "expand",
    "editor.cursorSmoothCaretAnimation": true,

2. Make sure the correct path is entered to your synthwave84.css! Save the file!
3. Once you've found synthwave84.css, open it and delete everything, then copy/paste the following into it:

.mtk1{
  color: #fefefe;
  text-shadow: 0 0 2px #100c0f, 0 0 99px #83a8d1, 0 0 10px #83a8d1;
}

4. Save the file. Then, in VS Code, hit CTRL+SHIFT+P -> Enable Neon Dreams.
5. Do CTRL+SHIFT+P -> Reload Custom CSS and JS.

You should all be set!

*UNINSTALL INSTRUCTIONS*
1. Disable the background extension (go to your Preferences (JSON) and set "background.enabled" to false);
2. Disable neon dreams (CTRL+SHIFT+P -> Disable Neon Dreams);
3. Reload custom js and css (CTRL+SHIFT+P -> Reload Custom JS AND CSS);
4. Uninstall this extension pack and other related extensions.