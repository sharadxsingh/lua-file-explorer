# 🗂️ Terminal File Explorer (Lua)  

A simple and lightweight terminal-based file explorer built in Lua. Navigate directories, open files, and interact with your filesystem using keyboard controls.  

## 🎯 Features  
✅ **Keyboard navigation** - Use `W/S` to move up and down  
✅ **Open files** - Press `O` to open files with the default application  
✅ **Enter directories** - Navigate into folders just like a real file manager  
✅ **Cross-platform support** - Works on **Linux**, **macOS**, and **Windows**  
✅ **Minimal and lightweight** - Only requires `Lua` and `LuaFileSystem (lfs)`  

## 🛠️ Installation  
1. Install **Lua** (if not installed):  
   - Linux/macOS: `sudo apt install lua5.4` (or `brew install lua`)  
   - Windows: Download from [lua.org](https://www.lua.org/download.html)  

2. Install **LuaFileSystem (lfs)**:  
   ```sh
   luarocks install luafilesystem
