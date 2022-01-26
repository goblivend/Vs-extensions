# Vs-extensions

A repository containing my VScode extensions

## To use

go to your extension folder :

```console
$ cd <extension folder>
```

In my case for wsl :

```console
$ cd ~/.vscode-server/extensions/
```

And for windows :

```console
$ cd C:\Users\<username>\.vscode\extension/
```

Then either copy each extension (folder) in this directory or create links (to simplify updates) :

```console
$ ln -s <path of the repo>/<extension>
```

For example :

```console
$ ln -s /mnt/c/documents/Vs-extensions/mysnippets/
```

This command will create a symbolic in the current folder to the file (/folder) you specified.

This way you can just have your code where you want and still be abble to use it as an extension

***

## to create one

### Installation

go to  <https://code.visualstudio.com/api/get-started/your-first-extension> and follow the tuto.
