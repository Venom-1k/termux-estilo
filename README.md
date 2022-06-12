<a href="https://ibb.co/F4XZCr1"><img src="https://i.ibb.co/v4hyRFW/20220612-145920.jpg" alt="20220612-145920" border="0"></a>

# Termux estilo 

![gif](images/main.gif) <br />

> *Script simples para alterar esquemas de cores e fontes para o emulador de terminal Termux*


### Como instalar

Siga os passos abaixo -

```bash
# atualiza ferramentas 
apt update

# instala git clone
pkg install git

# ir a home do terminal - 
cd $HOME

# clone  este repositório - 
git clone https://github.com/Venom-1k/termux-estilo

# obterá a pasta do repositório -
cd termux-estilo

# para instala o repositório -
bash start.sh

# isso irá ajudá-lo instalr as ferramentas no terminal .
```

### ver estilos de cor fonte etc..

digite `bash venom-estilo.sh ` -


<a href="https://ibb.co/KLBwzrh"><img src="https://i.ibb.co/Jy8QFst/20220612-145852.jpg" alt="20220612-145852" border="0"></a>
   
```bash
$ termux-estilo

     [*] By-  Venom Mods // ofc

    [C] Cor (89)
    [F] Fontes (20)
    [R] Aleatório
    [I]  importar
    [A] About
    [Q] sair
    
    [Selecions a opção]: 
```

### características

+ 90 esquemas de cores populares.
+ 20 fontes corrigidas powerline.
+ Altere aleatoriamente os esquemas de cores.
+ Importe esquemas de cores do arquivo local ou URL do arquivo .
+ Defina cores e fontes no lugar.

### Como importar
```bash
    [Selecione a opção ]: 4

    [1] Local do Arquivo (Enter com o arquivo)
    [2] Internet e os arquivos (Enter com URL)

    [Selecione a opção ]: 2

    [Enter cor e temas com  URL]: https://raw.githubusercontent.com/Venom-1k/termux-estilo/master/colors/gruvbox-dark.properties

    [*] Aplicando configurações...
    [*] Aplicado com sucesso. 
```

+ Para importar o arquivo local , digite o caminho completo (por exemplo-  (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) e esquemas de cor
+ Para importar o arquivo da web , digite a url do arquivo (por exemplo -(e.g. - `https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties`) e esquemas de co
<br />

### by venom
- Um `bash deleta.sh` também é adicionado, caso você queira remover esta script do termux.
- Venom agradeçe seu uso...
- Divirta-se!
