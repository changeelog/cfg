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
