

## Requisitos Obrigatórios:

* Neste projeto, você implementará um editor de arte com pixels.

**Ou seja, dada uma paleta de cores e um quadro composto por pixels, você vai permitir que quem usa consiga pintar o que quiser no quadro!** 👩‍🎨

### 1 - A página deve possuir o título "Paleta de Cores".

##### As seguintes verificações serão feitas:

- O título deverá ficar dentro de uma tag `h1` com o `id` denominado `title`;

- O texto do título deve ser **exatamente** "Paleta de Cores".

### 2 - A página deve possuir uma paleta de quatro cores distintas.

##### As seguintes verificações serão feitas:

- A paleta de cores deve ser um elemento com `id` denominado `color-palette`, ao passo que cada cor individual da paleta de cores deve possuir a `classe` `color`;

- A cor de fundo de cada elemento da paleta deverá ser a cor que o elemento representa. **A única cor não permitida na paleta é a cor branca.**;

- Cada elemento da paleta de cores deverá ter uma borda preta, sólida e com 1 pixel de largura;

- A paleta de cores deverá listar todas as cores disponíveis para utilização lado a lado, e deverá ser posicionada abaixo do título "Paleta de Cores";

- A paleta de cores não deve conter cores repetidas.

### 3 - A cor **preta** deve ser a primeira na paleta de cores.

##### As seguintes verificações serão feitas:

- As demais cores podem ser escolhidas livremente.

### 4 - A página deve possuir um quadro de pixels, com 25 pixels.

##### As seguintes verificações serão feitas:

- O quadro de "pixels" deve ter 5 elementos de largura e 5 elementos de comprimento;

- O quadro de "pixels" deve possuir o `id` denominado `pixel-board`, ao passo que cada "pixel" individual dentro do quadro deve possuir a `classe` denominada `pixel`;

- A cor inicial dos "pixels" dentro do quadro, ao abrir a página, deve ser branca;

-  O quadro de "pixels" deve aparecer abaixo da paleta de cores.

### 5 - Cada elemento do quadro de pixels deve possuir 40 _pixels_ de largura e 40 _pixels_ de altura e ser delimitado por uma borda preta de 1 pixel.

##### As seguintes verificações serão feitas:

- O quadro de pixels tem altura e comprimento de 5 elementos;

- 40 pixels deve ser o tamanho total do elemento, incluindo seu conteúdo e excluindo a borda preta, que deve ser criada à parte.

### 6 - Ao carregar a página, a cor **preta** da paleta já deve estar selecionada para pintar os pixels.

##### As seguintes verificações serão feitas:

- O elemento da cor preta deve possuir, inicialmente, a `classe` `selected`;

- Note que o elemento que deverá receber a classe `selected` deve ser um dos elementos que possuem a classe `color`, como especificado no **requisito 2**.

### 7 - Ao clicar em uma das cores da paleta, a cor selecionada é que vai ser usada para preencher os pixels no quadro.

##### As seguintes verificações serão feitas:

- A `classe` `selected` deve ser adicionada à cor selecionada na paleta, ao mesmo tempo em que é removida da cor anteriormente selecionada;

- Somente uma das cores da paleta deve ter a `classe` `selected` de cada vez;

- Note que os elementos que deverão receber a classe `selected` devem ser os mesmos elementos que possuem a classe `color`, como especificado no **requisito 2**.

### 8 - Ao clicar em um pixel dentro do quadro após selecionar uma cor na paleta, o pixel deve ser preenchido com esta cor.

##### As seguintes verificações serão feitas:

- Ao carregar a página deve ser possível pintar os pixels de preto;

- Após selecionar uma outra cor na paleta, deve ser possível pintar os pixels com essa cor;

- Somente o pixel que foi clicado deverá ser preenchido com a cor selecionada, sem influenciar na cor dos demais pixels.

### 9 - Crie um botão que, ao ser clicado, limpa o quadro preenchendo a cor de todos seus pixels com branco.

##### As seguintes verificações serão feitas:

- O botão deve ter o `id` denominado `clear-board`;

- O botão deve estar posicionado entre a paleta de cores e o quadro de pixels;

- O texto do botão deve ser **"Limpar"**.


#VQV 🚀
