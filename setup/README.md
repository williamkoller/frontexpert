# Por onde começar?

- Ferramentas:
  - vscode: 
    - instalar vscode: [vscode-download](https://code.visualstudio.com/)
    - fazer o download e acessar a pasta de download da sua maquina linux
    - `cd Downloads`
    - verificar se tem um download com a extensão .deb
    - rodar esse comando para instalacão, `sudo dpkg -i code..-.deb`

  - instalar extensões no vscode:
    - dracula
    - material icon theme
    - live server

  - instalar nodejs com nvm:
    - instalar nvm: [install nvm](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04-pt)
    - instalar a version do nodejs: `nvm install x.x.x`
    - instalar yarn global: `npm i -g yarn`

  - instalar git:
    - download para linux e unix: [linux](https://git-scm.com/download/linux)

  - config terminal:
    - instalar zsh: `sudo apt install zsh -y`
    - clone repo: `git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1`
    - symlink: `ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"`
    - set `ZSH_THEME="spaceship"` no seu `.zshrc`