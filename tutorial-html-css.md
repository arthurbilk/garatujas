# IA26 WebDesign
#### Atividade: reorganizar o texto disponibilizado via GitHub

## O que é HTML?

HTML - <strong>HyperText Markup Language (Linguagem de Marcação de Hipertexto)</strong> é uma linguagem de marcação textual, ou seja, de maneira simples, é o que estabelece a estrutura de um site ou texto. O HTML define oque é título, texto, sessão, rodapé e etc num site. Ele não serve pra deixar o site bonito, apenas organizado e estruturado para que todo tipo de pessoa possa usufruir do site, é como se o HTML fosse a estrutura de uma casa, os tijolos, as vigas e o telhado. A estilização (ou seja, a pintura, as janelas e etc) é o CSS.

### Como funciona o HTML?

O HTML precisa de certos artifícios para funcionar. O principal deles são as tags, que são literalmente a tradução (etiquetas), cada tag define oque cada elemento é, elas precisam (em sua maioria) ser abertas e fechadas: 
  - Abrir tag: ```<nome-da-tag>```
  - Fechar tag: ```</nome-da-tag>```
  
Alguns exemplos de tag são:

   - ```p```: usada para definir parágrafos.
   - ```hX```: usada para definir títulos e subtítulos. X = números de 1 a 6 (h1 é o título principal,
       h2 subtítulo e assim em diante).
   - ```body```: tudo que está aparente na página.
   - ```strong```: deixar em negrito.

Existem milhares de tags, incluindo diversas tags para o mesmo uso, então é muito difícil saber todas, o recomendável é pesquisar a tag necessária pra oque precisamos fazer no site. Além disso, devemos ter cuidado na hora de escolher as tags de mesma função, pois certas tags são puramente visuais, enquanto outras facilitam o entendimento de usuários com deficiência.

Para criar um site em HTML, é interessante pegar um papel e desenhar todo o conceito, depois, com o conceito finalizado, identificar cada elemento com sua respectiva tag e traduzir pro HTML.

### Estrutura básica de um HTML

A seguir, veremos um exemplo da estrutura básica de um documento em HTML:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
   <meta charset="UTF-8">
   <title>Título da Página</title>
   <!-- Links para arquivos CSS e scripts JavaScript podem ser adicionados aqui -->
</head>
<body>
   <!-- Conteúdo visível da página é adicionado aqui -->
</body>
</html>
```

Agora explicando cada tag:

- ```<!DOCTYPE html>```: marca o tipo de documento, nesse caso HTML5.
- ```<html lang="pt-BR">```: aqui temos 2 informações importantes, então:

  - ```<html ...>  </html>```: é a raiz do documento, se abre aqui e se fecha apenas na última linh.a
  - ```...lang="pt-BR"...```: define pro browser o idioma da página, facilitando a acessibilidade e otimizando a busca.

- ```<head>```: dentro dessa tag se localizam diversos dados importantes que não aparecem na página, como: metadados, links para CSS e Java, entre outros.

   - ```<meta charset="UTF-8">```: meta charset define que o grupo de caracteres da página é UTF-8.
   - ```<title>...</title>```: define o título da página pro browser.
 
- ```<body>...</body>```: todo o corpo da página, tudo que estiver aqui dentro é visto pelo usuário.

### Atributos HTML

Atributos são informações extras que colocamos nas tags HTML para dizer como algo deve funcionar. Exemplos de atributos são:

- ```href```: comumente usado com a tag ```<a>```, ```href``` serve pra definir o endereço do link contido na tag ```<a>```.
- ```src```: usado com a tag ```<img>```, indica o endereço da imagem para ela aperecer da maneira correta no site.
- ```alt```: também usado com a tag ```<img>```, ele indica uma alternativa caso o endereço contido em ```src``` seja inválido.

Um exemplo de uso da tag ```<a>``` com o atributo ```href``` é:

<a href="https://www.google.com">Visite o Google</a>
