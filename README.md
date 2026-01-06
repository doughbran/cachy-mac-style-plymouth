CachyOS Bootanimation Mac Style 🍏

Um tema de Plymouth elegante e minimalista inspirado no estilo visual do macOS, desenvolvido especialmente para o CachyOS.

🚀 Características

  Animação suave e moderna.
  Integração visual perfeita com a estética do CachyOS.
  Suporte a altas resoluções (HiDPI).

🛠️ Instalação no CachyOS

Como o CachyOS é baseado em Arch Linux, o processo é bem simples. Siga os passos abaixo no seu terminal:
1. Clonar o repositório

Primeiro, baixe os arquivos do tema:

    git clone https://github.com/doughbran/cachy-mac-style.git
    cd cachy-mac-style

2. Mover para a pasta de temas

Copie a pasta do tema para o diretório de sistemas do Plymouth:

    sudo cp -r cachy-mac-style /usr/share/plymouth/themes/

3. Configurar e Aplicar

Agora, defina o novo tema como padrão e atualize o initcpio (essencial no CachyOS/Arch para que o tema apareça no boot):

    sudo plymouth-set-default-theme -R cachy-mac-style

📝 Notas importantes

MKINITCPIO: O comando -R no passo 3 já tenta reconstruir a imagem do kernel. Se por acaso o tema não aparecer, execute manualmente:

    sudo mkinitcpio -P

📄 Licença

Este projeto está sob a licença MIT.

Criado por doughbran.
