### CONFIGURACION DE ZSHRC

Hay siete pasos de instalación para pasar de un terminal predeterminado a powerlevel9k terminal.

[Installation Instructions](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions)

1. [Tilix en ubuntu](https://gnunn1.github.io/tilix-web/)

   ```shell
   $ sudo apt install tilix
   ```

2. [Oh my zsh en ubuntu](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)

   ##### via curl

   ```shell
   $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   ```

   ##### via wget

   ```shell
   $ sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   ```

3. [Install the Powerlevel9k Theme](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions#step-1-install-powerlevel9k)

   ```shell
   $ git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
   ```

4. [Install Powerline Fonts](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack/Regular/complete)

   ##### `Hack Regular Nerd Font Complete.ttf`

5. [Mapear Caracteres](https://bluejamesbond.github.io/CharacterMap/)

   > Seleccionar la fuente descargada para poder mapear los caracteres integradas.

6. [Reemplazar configuracion](https://github.com/mcra02/bash-configuration)

   > Descargar o copiar la configuracion del archivo `.zshrc.conf` del repositorio a `.zshrc`.

7. Recargar .zshrc

   ```shell
   $ source .zshrc
   ```
