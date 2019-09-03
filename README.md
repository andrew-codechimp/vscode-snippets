# vscode-snippets
Various snippets for VS Code

Looking for LMS Slim Snippets?  I've now published these as a proper VSCode Extension for easy installation & updates  
https://marketplace.visualstudio.com/items?itemName=CodeChimp.lmsslim-snippets

Source https://github.com/codechimp-org/vscode-lmsslim-snippets

This repo will contain random snippets for all other projects.

Either copy the files within the snippets folder to your VS Code global snippets location or setup a symlink.

## Mac
Global snippets are stored in your user library application support folder, I use a symlink from the checkout directory for this repo  
```ln -s /Users/<USER>/<YOUR FOLDER>/vscode-snippets/snippets/ /Users/<USER>/Library/Application\ Support/Code/User/snippets```

## Windows
Global snippets are stored in your user AppData folder, I use a symlink from the checkout directory for this repo  
```mklink /D c:\Users\<USER>\AppData\Roaming\Code\User\snippets c:\<YOUR FOLDER>\vscode-snippets\snippets```
