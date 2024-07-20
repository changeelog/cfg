![banner](https://github.com/changeelog/static/blob/main/cfg-banner.png?raw=true)

## 🎨 Color Themes

🔝 Go to top

I usually use Vitesse Light Soft as my light theme. I only use it in the early morning and possibly during the day. This one is most pleasing to the eye.

![code sampple light](https://github.com/changeelog/static/blob/main/cfg/code_2.png?raw=true)

🔝 Go top top

I usually use Minimal Kiwi as my primary dark theme. I can switch to others - it's either Min Dark or Vitesse Dark Soft.

![code sampple dark](https://github.com/changeelog/static/blob/main/cfg/code_1.png?raw=true)

## 📝 Icon Theme

I have tried a huge number of icon sets and I like City Lights Icon Theme (Visual Studio Code) - Black & White and Seedling Icon Theme+ (with folder icon) the best. I usually prefer the first one. I change it quite rarely, because the sidebar is usually hidden and opened by shortcut.

### City Lights Icon Theme

![city lights icon theme gif](https://github.com/changeelog/static/blob/main/cfg/city-lights.gif?raw=true)

### Seedling Icon Theme

![seedling icon theme gif](https://github.com/changeelog/static/blob/main/cfg/seedling.png?raw=true)

## 📝 Snippets

### Batch File

🔝 Go top top

| Prefix | Body                                                                                                          | Description                            |
| ------ | ------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| header | @echo off<br>setlocal enabledelayedexpansion<br><br>rem ${1:Script description}<br><br>$0                     | Create a basic batch file header       |
| for    | for %%${1:i} in (${2:item1 item2 item3}) do (<br> echo %%${1:i}<br> $0<br>)                                   | Create a for loop in batch             |
| if     | if ${1:condition} (<br> $0<br>) else (<br> <br>)                                                              | Create an if-else statement in batch   |
| func   | :${1:functionName}<br>$0<br>goto :eof                                                                         | Create a function in batch             |
| set    | set &quot;${1:variableName}=${2:value}&quot;                                                                  | Set a variable in batch                |
| input  | set /p &quot;${1:variableName}=${2:Enter a value: }&quot;                                                     | Read user input in batch               |
| error  | if errorlevel 1 (<br> echo An error occurred<br> exit /b 1<br>)                                               | Basic error handling in batch          |
| exists | if exist &quot;${1:filename}&quot; (<br> echo File exists<br>) else (<br> echo File does not exist<br>)       | Check if a file exists in batch        |
| mkdir  | if not exist &quot;${1:directoryPath}&quot; mkdir &quot;${1:directoryPath}&quot;                              | Create a directory if it doesn't exist |
| args   | if &quot;%1&quot;==&quot;&quot; (<br> echo Usage: %0 <argument><br> exit /b 1<br>)<br>set &quot;arg1=%1&quot; | Handle command line arguments in batch |

### CSS

🔝 Go top top

...

## User Settings (settins.json)

These user settings are crafted to provide a refined and efficient development experience in Visual Studio Code. The settings focus on enhancing readability, minimizing distractions, and optimizing the overall workflow. Let's dive into the key aspects of these settings:

- **Font and Typography:** The settings utilize the "Monaspace Neon" font family for the editor, with a font size of 13 and a line height of 1.5. The slight letter spacing of 0.1 improves readability. The consistent use of "JetBrains Mono" and "Geist Mono" fonts across various UI elements ensures a cohesive and visually pleasing experience.
- **Minimalistic UI:** The settings aim to minimize distractions by disabling certain UI elements such as breadcrumbs, the activity bar, and the minimap. The editor's line highlight is set to "gutter" to maintain a clean and focused view. The compact folders setting in the explorer further reduces visual clutter.
- **File Nesting Patterns:** An extensive set of file nesting patterns is defined to group related files together in the explorer. This feature enhances navigation and reduces the need to search for associated files manually. The patterns cover a wide range of file types and naming conventions commonly used in various programming languages and frameworks.
Terminal and Integrated Terminal: The "terminal.integrated.fontFamily" setting specifies "JetBrains Mono" as the font family for the integrated terminal, ensuring a consistent visual experience.
- **Smooth Animations:** The "editor.cursorSmoothCaretAnimation" and "workbench.list.smoothScrolling" settings enable smooth animations for the cursor and list scrolling, providing a polished and fluid user experience.
