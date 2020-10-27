# Download-Imagem-URL-Sketchware
Fazer o download de uma imagem via URL pelo Sketchware

## Fazendo o download de uma imagem via URL pelo Sketchware

### :cherries: Para começarmos o tutorial, pesquise na comunidade do sketchware pelo seguinte moreblock: "download" e baixe-o.

![Print 1](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-145804.png)

## :page_facing_up: Tutorial: 

### Agora criaremos mais uma tela. Essa tela vai se chamar: "tela_2".

### Faça como na imagem:

![Print 2](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-130253.png)

## :iphone: Tela 1. main.xml:

### Na primeira tela colocaremos uma linear e um button. como na imagem:

![Print 3](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-131125.png)

### Na onClick do Button adicionaremos um componente Intent. Como mostra na imagem:

![Print 4](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-130116.png)

### Agora colocaremos os seguintes blocos:

1. Intent Definir Tela ( Marque a tela 2).
2. Intent Colocar Chave Extra Valor ( Na chave coloque como "foto" e no valor coloque o link da imagem).
3. Intent Iniciar Atividade.

Agora marque os blocos.

### Faça como na imagem:

![Print 5](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-145935.png)

## :iphone: Tela 2. tela_2.xml:

### Na segunda tela colocaremos uma linear, um button e uma imageview. como na imagem:

![Print 6](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-131137.png)

### Agora na onCreate adicionaremos duas variáveis strings.

A primeira variável string se chamará "wall"
 e a segunda "string".
 
 ![Print 10](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-130648.png)
 
 ![Print 11](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-130703.png)
 
### Agora continuando na onCreate faça a seguinte lógica:
 
 ![Print 8](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-131359.png)
 
 No bloco "Obter Chave Extra", coloque a chave "foto". E no bloco "Definir string para" coloque o caminho como "/Wallpapers" ou o que preferir. Mas lembre-se de seguir a lógica da foto acima. Agora marque todas as strings e espaços como "wall", como mostra na foto.
 
 ## :bulb: onClick Button:
 
 ### Agora na onClick do Button faça a seguinte lógica:
 
 ![Print 12](https://github.com/Gabriel-True/Download-Imagem-URL-Sketchware/blob/main/Screenshot_20201027-131453.png)
 
 Adicione o moreblock que você baixou. Coloque o bloco "Obter Chave Extra" e coloque como "foto". No outro espaço marque como "wall". 
 
 Agora adicione mais um bloco embaixo do moreblock, coloque o bloco "definir string para" e adicione o bloco "Obter Chave Extra" e escreva a chave como "foto". Marque a string do segundo bloco como "string". Faça do mesmo jeito que a imagem acima.
 
 ### :smiley_cat: Pronto, agora compile o projeto e veja como ficou. 
 

