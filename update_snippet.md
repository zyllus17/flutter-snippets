1. Increment the version number in `package.json` file.
2. You must have npm installed on the system.
3. Open terminal and type the following commands
- npm install -g vsce
- Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
- vsce package
4. The command will create a .vsix file.
5. Open this [link](https://marketplace.visualstudio.com/manage/publishers/marufhassan) and click on the three dots on the Extension you want to update and press Update.
6. Drop the .vsix file and your extension will be updated.