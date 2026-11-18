# Dicionário de Matemática em Haskell

Projeto educacional de terminal que organiza fórmulas de álgebra, geometria e estatística em módulos Haskell. Esta pasta é um projeto de programação, não uma aplicação web; a página do GitHub Pages funciona como uma apresentação do código.

## Estrutura

- `src/Algebra.hs`: Bhaskara, fatorial, Fibonacci e números primos.
- `src/Geometry.hs`: áreas e volumes de figuras geométricas.
- `src/Statistics.hs`: média, variância e desvio padrão.
- `src/Main.hs`: ponto de entrada e exemplos de uso.
- `math-dictionary.cabal`: configuração do pacote Cabal.

## Requisitos e execução

Instale o [GHC](https://www.haskell.org/ghc/) e o [Cabal](https://www.haskell.org/cabal/), então execute:

```bash
git clone https://github.com/gabrielaraujo-eng/math-dictionary-haskell.git
cd math-dictionary-haskell
cabal run math-dictionary
```

## GitHub Pages

O workflow em `.github/workflows/pages.yml` publica a página de apresentação. Para ativar a publicação pela primeira vez, abra **Settings → Pages** no repositório e selecione **GitHub Actions** como fonte.

URL esperada: <https://gabrielaraujo-eng.github.io/math-dictionary-haskell/>

## Créditos

Desenvolvido por Gabriel Lúcio de Araújo como estudo de programação funcional aplicada à matemática.
