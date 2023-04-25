# Data Lovers


## Índice

* [1. Resumo do projeto](#1-resumo-do-projeto)
* [2. Interface](#2-interface)
* [3. Responsividade](#3-responsividade)
* [4. Organização de trabalho](#4-organização-de-trabalho)
* [5. Testes unitários](#5-testes-unitários)


***


## 1. Resumo do projeto

Neste projeto construímos uma página web pensando nas necessidades do nosso usuário
de acessar alguns dados sobre o Studio Ghibli.

Em nossa página ele poderá visualizar dados, ou seja, os filmes que foram feitos 
pelo studio, e ordená-los de A a Z ou Z a A. É possível filtrá-los por diretor,
e ver qual o percentual de filmes foram produzidos pelo mesmo. Também poderá filtrar
os personagens por filmes e saber quantos personagens aquele filme tem e alguns dados
sobre eles.

- ***Para acessar a página web [clique aqui](https://daphnevilhar.github.io/SAP009-data-lovers/src/index.html).***

Foi desenvolvido em HTML, CSS e JavaScript.

## 2. Interface

Temos uma tela de início onde o usuário tem um pequeno resumo sobre o Studio Ghibli:

![tela_inicio](https://user-images.githubusercontent.com/122536567/226693408-0cb19a4e-9dfe-4110-ac56-bc966a57bd10.png)

Então poderá acessar os cards com imagem, diretor, ano e nome dos filmes e também poderá ordená-los:

![tela_filmes](https://user-images.githubusercontent.com/122536567/226691782-e8b340c8-bcb8-43be-8afb-58f7dd37e41f.png)

Com o filtro de diretor aparecerá os filmes dirigidos pelo mesmo e a porcentagem de filmes dele no estúdio:

![tela_filtro_diretor](https://user-images.githubusercontent.com/122536567/226691979-7650c0a1-1266-4851-b6bc-8b1436ba582b.png)

É possivel também filtrar os personagens por filmes e ver quantos personagens aquele filme tem. Ver seus nomes, idade, gênero e espécie:

![tela_personagens](https://user-images.githubusercontent.com/122536567/226692064-88cc50f8-4c3c-48c1-831a-d2d848d78064.png)


## 3. Responsividade

Sabendo que os usuários hoje acessam mais as páginas pelo smartphone, foi desenvolvida de forma responsiva adaptando-se a todos os tamanhos de tela.


![tela_inicio_mobile](https://user-images.githubusercontent.com/122536567/226697344-c1cdc153-2420-4a24-ae9b-9796aa0fd7ee.png)![tela_cards_mobile](https://user-images.githubusercontent.com/122536567/226696288-70ba0579-0013-404d-8ef4-b5c8959d0975.png)

&nbsp;

### 4. Organização de trabalho

Antes do desenvolvimento foram feitas histórias de usuário, como por exemplo:

- Eu como pessoa que assisti aventuras de shiriro quero saber quais são os outros filmes para que eu possa assistir.

- Eu como fã de cinema quero saber quem são os diretores e produtores pra saber mais sobre suas obras.

- Eu como namorado de uma fã de studio ghibli quero saber quais são os personagens do filme favorito dela pra comprar um presente.

- Eu que conheci o studio agora quero saber quantos filmes foram feitos para matar minha curiosidade.

Também foram feitos protótipos pelo figma. Para organização durante as sprints dividimos o projeto em pequenas tarefas
utilizando o trello como plataforma.

### 5. Testes unitários

Foram construídos e tiveram 100% de _statements_
(_sentenças_), _functions_ (_funções_), _lines_ (_linhas_), e _branches_
(_ramos_) do arquivo `src/data.js`.
