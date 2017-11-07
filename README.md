# 1 - Instale o Homebrew ![Homebrew Logo](https://assets-cdn.github.com/images/icons/emoji/unicode/1f37a.png)

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# 2 - Instale o Fish Shell 
![Fish Logo](https://fishshell.com/assets/img/screenshots/autosuggestion.png)
https://fishshell.com/

```sh
brew install fish
```

# 3 - Instale o Iterm2 
![Iterm logo](https://tighten.co/assets/img/blog/tools-iterm.jpg)

https://www.iterm2.com/

# customizar_iterm2
Links explicativos para customização do iterm2 do mac os x

# Primeiro método
1 - iTerm e Oh My Zsh

Iterm2: https://www.iterm2.com/

Comandos úteis:
Cmd + D para split vertical
Cmd + Shift + D para split horizontal
Cmd + F para pesquisar

#Oh My Zsh

Instalar:

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

github do projeto: https://github.com/robbyrussell/oh-my-zsh

# Esquema de cores Solarized

Instalar:
curl -o ~/Downloads/solarized.itermcolors https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors

Para utilizar o tema, entrar no Iterm e Cmd + i para abrir as preferências, vá na aba Colors e na caixa de seleção Color Presets, selecione import e localize o arquivo baixado.

#Meslo Font

git clone https://github.com/powerline/fonts.git && cd fonts && ./install.sh

Cmd + i novamente, vá na aba Text e altere Font e Non-ASCII Font para Meslo LG L for Powerline.

#Tema Agnoster para Oh My Zsh

Abra o arquivo ~/.zshrc com um editor de texto e mude o parâmetro ZSH_THEME para agnoster.

code ~/.zshrc

Dentro do arquivo trocar a linha: ZSH_THEME="agnoster"

#Outros métodos:

https://gist.github.com/kevin-smets/8568070

# Segundo método

#Oh My Fish
https://github.com/oh-my-fish/oh-my-fish

# 4 - Instale o Visutal Studio Code

https://code.visualstudio.com/



