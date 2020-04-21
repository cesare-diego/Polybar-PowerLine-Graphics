# Polybar-PowerLine-Graphics

Instalação:

# Etapa 1

1- yay -S polybar
2- mkdir .config/polibar
3- cd Polybar-Powerline-Graphics
4- cp config ~/.config/polybar
5- cp -r scripts ~/.config/polybar
6- cd fonts
7- sudo cp -r * /usr/share/fonts

# Etapa 2

1- Use seu editor de texto e edite o arquivo de configurações do i3.
Exemplo "vim .config/i3/config"
2 - No fim do arquivo inclua as seguintes linhas.
exec --no-startup-id polybar -r mybar &
exec --no-startup-id polybar -r bottom &
Essas linhas farão com que o Polybar inicie no boot do sistema

# Etapa 3

Essa configuração usa o jgmenu como menu, para que ele funcione voçe de seguir os seguintes
passos.

1- sudo pacman -s jgmenu
2- para mudar o tema do jgmenu basta copiar e colar os comandos dessa pagina.
https://jgmenu.github.io/screenshots.html
3- Voçe pode editar esses temas dentro de .config/jgmenu/jgmenurcm.






