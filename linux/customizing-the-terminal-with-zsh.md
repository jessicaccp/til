# Customizing the terminal with ZSH

- **Install zsh**
```
$ sudo dnf install zsh
```

- **Install oh-my-zsh**
  - via wget
```
$ sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```
  - via curl
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

- **Logout and login**

- **Look for a [theme](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)**

- **Configure zsh and change the theme**
```
$ nano ~/.zshrc
ZSH_THEME="<theme-name>"
```

> Now, instead of setting up things in `~/.bashrc`, set up in `~/.zshrc`

- **If you want to undo the change and use bash again**
```
$ chsh /bin/bash
```

