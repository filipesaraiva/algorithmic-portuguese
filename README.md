# algorithmic-portuguese
`algorithmic-portuguese` traduz para português as palavras reservadas utilizadas
na criação de algoritmos pelo pacote LaTeX [`algorithmic`]
(https://www.ctan.org/pkg/algorithms).

## Como usar
Salve o arquivo [algorithmic-portuguese.tex](https://gitlab.com/filipesaraiva/
algorithmic-portuguese/raw/master/algorithmic-portuguese.tex) na pasta do seu
projeto.

A seguir, após carregar o pacote `algorithmic` e antes de iniciar o texto do
documento LaTeX, insira o comando `\input{algorithmic-portuguese}`, como abaixo:

```latex
\include{algorithmic}
...
\input{algorithmic-portuguese}
...
\begin{document}
```

Os comandos LaTeX a serem utilizados serão os mesmos apresentados no [manual do
pacote algorithms (PDF)](http://mirrors.ctan.org/macros/latex/contrib/
algorithms/algorithms.pdf). Apenas a apresentação dos algoritmos no documento
gerado será feita em português.

## Licença

Esse projeto é disponibilizado sob a licença [GNU All-Permissive License]
(http://www.gnu.org/licenses/license-list.en.html#GNUAllPermissive), o que
permite a utilização em qualquer documento ou projeto, seja livre ou fechado,
sem qualquer ônus, exigindo-se apenas a manutenção da nota de *copyright*
original no arquivo do `algorithmic-portuguese`.
