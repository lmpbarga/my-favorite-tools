# My Favorite Tools

## IDE
VsCode

## Terminal
[Criando um ambiente de Desenvolvimento no Windows](https://www.youtube.com/watch?v=YcR8pKvjx44&list=PLlAbYrWSYTiOpefWtd6uvwgKT1R-94Zfd&ab_channel=WillianJustenCursos) by Willian Justen

### zsh && oh-my-zsh && zsh-autosuggestions

```sh
sudo apt install zsh
```

```sh
nano ~/.bashrc
```

```sh
# add in .bashrc file
exec zsh
```

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```sh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```sh
nano ~/.zshrc
```

```sh
plugins=( 
    # other plugins...
    zsh-autosuggestions
)
```

### SSH in Zsh
[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) by Github

```sh
ssh-keygen -t rsa
```

```sh
nano ~/.zshrc
```

```sh
plugins=( 
    # other plugins...
    ssh-agent
)
```

```sh
cd ~/.ssh
```

```sh
more id_rsa.pub
```

### NVM
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

### Node
```sh
nvm install stable
```

### Yarn
```sh
npm install --global yarn
```

### Nodemon
```sh
npm install --global nodemon
```