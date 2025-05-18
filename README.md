Сохранить список в файл:
```sh
code --list-extensions > vscode_extensions.txt
```

Установка и восстановление по списку:
```sh
cat vscode_extensions.txt | xargs -L 1 code --install-extension
```