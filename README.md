# Pense em Python

Tradução do livro [Think Python](http://greenteapress.com/wp/think-python-2e/) (2ª edição), de Allen B. Downey, publicado sob licença [CC BY-NC 3.0](LICENSE.md).

[Versão navegável em HTML](https://PenseAllen.github.io/PensePython2/)


## Proveniência

Agradecemos a Rubens Prates da Editora Novatec por ter cedido gentilmente os arquivos com o texto integral e as figuras de [Pense em Python](https://novatec.com.br/livros/pense-em-python/), publicado sob licença da O'Reilly Media.

O arquivo [`recebido/PenseEmPython.xml`](recebido/PenseEmPython.xml) em formato DocBook foi gerado a partir do arquivo InDesign criado pela Editora Novatec. Na conversão para DocBook foram usados os programas InDesign, Word e LibreOffice.

O DocBook `PenseEmPython.xml` foi convertido para _markdown_ com a ferramenta Pandoc versão 1.19.2.1 usando a seguinte linha de comando:

```bash
$ pandoc PenseEmPython.xml -f docbook -t markdown_github -o PenseEmPython.md
```

Os arquivos _markdown_ separados por capítulo em [`recebido/docs/`](recebido/docs/) foram gerados a partir de `PenseEmPython.md` pelo script [`util/separar_capitulos.py`](util/separar_capitulos.py).

A partir desse ponto, os ajustes nos capítulos foram feitos manualmente, com ajuda ocasional de scripts encontrados no diretório [`util/`](util/).


## Créditos da edição brasileira

Editor: Rubens Prates<br>
Tradução: Sheila Gomes<br>
Revisão Gramatical: Smirna Cavalheiro<br>
Editoração Eletrônica: Carolina Kuwabata<br>
Assistente Editorial: Priscila A. Yoshimatsu
