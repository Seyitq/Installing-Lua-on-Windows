# Installing Lua on Windows
Lua is a powerful, fast, lightweight, embeddable scripting language. The Lua virtual machine and interpreter are written in C. As a language, Lua is easy to learn. It contains 21 keywords, which makes the language rather small. Lua is also easy to read and understand, as its syntax makes it similar to English. For example, consider the following code snippet:
```lua
if not hero:IsAlive() then
 GameOver();
end
```
This code is easy to read, and I bet you can take an intuitive guess at what it does. Lua is not only easy to read, it is also very powerful. The real power of Lua comes from its extensible nature. Programming constructs such as object-oriented programming (OOP) can be implemented in Lua, even though the language has no native support for objects.

At the time of writing, Lua has 14 versions; this book will focus on Lua 5.2.4. The latest version is 5.3; the main difference between 5.2 and 5.3 is that 5.3 contains support for explicit integers and bitwise operation.

## Source code and binaries
Lua is open source software published under the MIT License. You can browse Lua's source code at https://www.lua.org/source/. Additionally, you can download both the source code and reference manuals for Lua from https://www.lua.org/ftp/.

At the time of writing, no pre-built binaries are downloadable from the lua.org website. Pre-built binaries can be found on SourceForge at https://sourceforge.net/projects/luabinaries/. In this chapter, we will be using SourceForge to download binaries for Lua.

### Installing Lua on Windows 10
Follow these steps to install Lua 5.2.4 on Windows 10. These instructions are written for Windows 10, but the steps needed to install should be similar on older (and future) versions of Windows as well:

1. To download Lua 5.2.4, visit https://sourceforge.net/projects/luabinaries/files/5.2.4/.
2. Click on the Tools and Executables link.
3. On a 32-bit version of Windows, click the lua-5.2.4_Win32_bin.zip link to start downloading Lua. On a 64-bit version of Windows, click the lua-5.2.4_Win64_bin.zip      link   to start downloading.
4. Once the file is downloaded, unzip the file. Unzipping the downloaded file should create four new files: lua52.dll, lua52.exe, luac52.exe, and wlua52.exe.
5. Create a new folder inside C:\Program Files, and call this new folder LUA. Copy the four files you just unzipped into this directory.
6. Rename lua52.exe to lua.exe. If your Windows installation is set up to hide file extensions, rename lua52 to lua:
 ![image1](https://raw.githubusercontent.com/Seyitq/Installing-Lua-on-Windows/main/lua/1.png)
7. The path to Lua needs to be set up as an environment variable in Windows.
8. Right-click on the Start/Windows menu button and select the System option.
9. From the System window, select the Advanced Settings option.
10. Having clicked the Advanced Settings option, you should now see the System Properties dialog. In this dialog, click on the Environment Variables... button.
11. In the Environment Variables window, with the Path variable selected, click the Edit... button:
 ![image2](https://raw.githubusercontent.com/Seyitq/Installing-Lua-on-Windows/main/lua/2.png)
12. The path to Lua needs to be set up as an environment variable in Windows.
13. Right-click on the Start/Windows menu button and select the System option.
14. From the System window, select the Advanced Settings option.
15. Having clicked the Advanced Settings option, you should now see the System Properties dialog. In this dialog, click on the Environment Variables... button.
16.(final step) In the Environment Variables window, with the Path variable selected, click the Edit... button:
 ![image3](https://raw.githubusercontent.com/Seyitq/Installing-Lua-on-Windows/main/lua/3.png)
