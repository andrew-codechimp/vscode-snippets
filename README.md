# vscode-snippets
Various snippets for VS Code

Includes:  
* Perl
* Slim framework (Logitech Media Server)

Either copy the files within the snippets folder to your VS Code global snippets location or setup a symlink.

## Mac
Global snippets are stored in your user library application support folder, I use a symlink from the checkout directory for this repo  
```ln -s /Users/<USER>/<YOUR FOLDER>/vscode-snippets/snippets/ /Users/<USER>/Library/Application\ Support/Code/User/snippets```

## Windows
Global snippets are stored in your user AppData folder, I use a symlink from the checkout directory for this repo  
```mklink /D c:\Users\<USER>\AppData\Roaming\Code\User\snippets c:\<YOUR FOLDER>\vscode-snippets\snippets```
