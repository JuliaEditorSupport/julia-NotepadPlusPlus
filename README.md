# Notepad++

[Julia language](https://julialang.org/) support for [Notepad++](https://notepad-plus-plus.org/)

- Syntax highlighting
- Auto Hotkey

## Installation
### Manual installation
For Syntax Highlighting
- Download the xml file from below or copy the content in an empty text file and save it as an xml
- Open Notepad++ and go to the menu entry *Language > Define your language ...*
- Click *Import...* and select the downloaded xml file
- Restart Notepad++ (actually, this should not be necessary, but it is recommended)
*julia* should be listed now in the *Language* menu. 

For Auto Hotkey
- Download and install AutoHotkey for Windows if not already installed on your computer
- Download the ahk file from below or copy the content in an empty text file and save it as an ahk
- Open Command Prompt and go the the folder the ahk file is at
- Run the script with `start AutoHotkey Notepad++_2_Julia.ahk`
- Greek letters are now availible in the current windows session using key combination `ctr` + `win` + [letter key] 
- E.g. for ε the key combination is `ctr` + `win` + `e`


### Content
| Name                           |  Description                                                |
| ------------------------------ | ----------------------------------------------------------- |
|[ Julia_Notepad++.xml ](Julia_Notepad++.xml) | Notepad++ config file |
|[ Notepad++_2_Julia.ahk ](Notepad++_2_Julia.ahk) | Auto Hotkey for Notepad++ config file |

## Contributing
We love contributors but please first read the general guide about [contributing to Julia language project](https://github.com/JuliaLang/julia/blob/master/CONTRIBUTING.md).

If **necessary**, [open an issue](https://github.com/JuliaEditorSupport/julia-NotepadPlusPlus/issues).

### Contributor list
- Everyone who contribute to files to Notepad++ plugins for Julia development [JuliaLang/julia/contrib](https://github.com/JuliaLang/julia/tree/5b95805fc73abe672a85ef04249cf34378ec9f74/contrib):
  - [Julia_Notepad++.xml](https://github.com/JuliaLang/julia/blob/f8a44d52f80a120f7595995f8d6d8c31b84cf7dd/contrib/Julia_Notepad%2B%2B.xml)
  - [Notepad++_2_Julia.ahk](https://github.com/JuliaLang/julia/blob/4e4663e13e837eb6bc617125c830ac956e1d96ed/contrib/Notepad%2B%2B_2_Julia.ahk)
- [See contributors](https://github.com/JuliaEditorSupport/julia-NotepadPlusPlus/graphs/contributors)
