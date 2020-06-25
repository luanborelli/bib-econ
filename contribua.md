# Como contribuir


### Sugerindo a inclusão de livros

Você pode sugerir a inclusão de livros entrando em contato com [Luan Borelli](https://twitter.com/BorelliLuan) ou [Marcelo Gelati](https://twitter.com/marcelogelati) pelo Twitter ou pelos e-mails [contato@luanborelli.net](mailto:contato@luanborelli.net) ou [marcelogelati@gmail.com](mailto:marcelogelati@gmail.com).

### Adicionando um novo livro por conta própria

Antes de qualquer coisa, VERIFIQUE SE O LIVRO QUE VOCÊ ADICIONARÁ AINDA NÃO FOI ADICIONADO. Depois, leia nosso [critério de classificação](classificacao.md) de dificuldade para que você proponha a inclusão do livro o classificando na dificuldade adequada. 

Para propor a adição de um livro faça um pull request. Se você não sabe efetuar um pull request, [aprenda aqui](https://help.github.com/pt/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request). Faça UM PULL REQUEST POR LIVRO.

No título do pull request, informe o nome do livro

Os livros são ordenados em ordem alfabética com base no primeiro nome do primeiro autor. Portanto, posicione o seu livro na lista de acordo com essa regra.

O livro deve ser inserido no formato:

```
### Nome dos autores, *Nome do livro*

**[[@SeuTwitter](https://twitter.com/marcelogelati)]** Descrição opcional. Fale um pouco sobre o livro, apreciamos comparações com pares (ex.: Esse livro difere do livro X pois tem um tratamento um pouco mais/menos formal. Tem mais exemplos do que o livro X. Tem mais exercícios do que o livro Y. [[AMZN]](link do livro na Amazon)
```

Exemplo:
```
### Hal Varian, *Microeconomia*

**[[@marcelogelati](https://twitter.com/marcelogelati)]** Este livro é o primeiro contato mais aprofundado com microeconomia. Apesar disso, o livro não pede um curso de cálculo como pré-requisito. [[AMZN]](https://www.amazon.com.br/Microeconomia-Hal-Varian/dp/8535230181/)
```

Resultado:

---

### Hal Varian, *Microeconomia*

**[[@marcelogelati](https://twitter.com/marcelogelati)]** Este livro é o primeiro contato mais aprofundado com microeconomia. Apesar disso, o livro não pede um curso de cálculo como pré-requisito. [[AMZN]](https://www.amazon.com.br/Microeconomia-Hal-Varian/dp/8535230181/)

---

Algumas observações cabem aqui. Em primeiro lugar, a tag `[[@SeuTwitter]](twitter.com/SeuTwitter)` apenas deve constar caso você inclua uma descrição para o livro. Se nenhuma discussão for incluída, essa tag não deve ser utilizada. O objetivo dela é informar o autor da descrição. Em segundo lugar, se você não possui Twitter, troque a tag `[[@SeuTwitter]](twitter.com/SeuTwitter)` por `[[SeuGithub]](github.com/SeuGithub)`. Em terceiro lugar, se o livro não estiver disponível na Amazon, troque a tag `[[AMZN]](link do livro na Amazon)` por `[[LINK]](link para o livro)` e coloque um link direcionando para onde o livro possa ser adquirido. Links que levem direto para o PDF do livro serão aceitos e apreciados SE, E SOMENTE SE, o livros estiver legalmente sendo disponibilizado abertamente ao público.

### Adicionando uma descrição

Muitos livros foram incluídos sem descrição. Uma forma de contribuir é incluindo uma decrição a um livro que ainda não possua uma. As descrições deverão ser incluídas também por meio de [pull requests](https://help.github.com/pt/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) e devem seguir o mesmo modelo exposto acima. O conteúdo das descrições é livre, contudo, apreciamos comparações com pares que auxiliem o leitor na escolha do livro que mais lhe convenha (ex.: Este livro difere do livro X pois tem um tratamento um pouco mais/menos formal. Possui mais/menos exemplos do que o livro X. Possui mais/menos exercícios do que o livro Y.)

### Discutindo

Se você discorda de alguma classificação (seja de dificuldade ou seja de tema) ou discorda de alguma informação contida em alguma descrição de algum livro, você pode discuti-la por meio da [abertura de uma Issue](https://github.com/luanborelli/bib-econ/issues). 


