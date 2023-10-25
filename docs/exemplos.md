# Exemplos

Exemplo de como fazer alguns componentes com markdown no mkdocs. A documentação completa pode ser encontrada [aqui](https://squidfunk.github.io/mkdocs-material/reference/lists/)

# h1

## h2

### h3

#### h4

##### h5

###### h6

`texto destacado`

*italico*

**negrito**

> citação

==Marca texto==

^^Underline^^

~~Riscado~~

[Link](https://www.pneustore.com.br/)

++ctrl+alt+del++ ++enter++

/// admonition | Fixo
    type: warning
Conteudo
///

/// details | Expansivo
    type: danger
Conteudo
///


-   [X] item 1
    *   [X] item A
    *   [ ] item B 
    more text
        +   [x] item a
        +   [ ] item b
        +   [x] item c
    *   [X] item C
-   [ ] item 2
-   [ ] item 3

<br/>

- item 1
    - item 2
    - item 3
- item 4
    - item 5
        - item 6

<br/>

1. item 1
    1. item 2
    2. item 3
2. item 4
    2. item 5
        2. item 6

<br/>

| Sistema | Descrição |
|--|--|
| Hybris | PneuStore |
| Spartacus | CantuPneus |

[Botão](#){ .md-button }

=== "Tab 1"
    Conteudo do tab 1

=== "Tab 2"
    Conteudo do tab 2


``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

Imagem
![Imagem](https://images.freeimages.com/variants/k1wQB7egQotJ7Hr3ZBPP1S5c/f4a36f6589a0e50e702740b15352bc00e4bfaf6f58bd4db850e167794d05993d)