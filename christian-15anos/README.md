# Feliz 15 Anos, Christian

## Estrutura de pastas

```
christian-15anos/
├── index.html
├── README.md
└── assets/
    ├── images/
    │   └── christian.jpg        ← foto dele (seção "Coisas que eu amo em você")
    └── audio/
        ├── musica-dele.mp3      ← música que ELE dedicou ao namoro (player esquerdo)
        └── musica-minha.mp3     ← música que VOCÊ dedicou ao namoro (player direito)
```

---

## Como colocar a foto

1. Renomeie o arquivo para `christian.jpg`
2. Coloque dentro de `assets/images/`
3. No `index.html`, encontre o bloco `.amor-photo-placeholder` e substitua por:

```html
<img src="assets/images/christian.jpg" alt="Christian">
```

---

## Como colocar as músicas

1. Renomeie os arquivos `.mp3`:
   - A música que **ele** dedicou: `musica-dele.mp3`
   - A música que **você** dedicou: `musica-minha.mp3`
2. Coloque os dois dentro de `assets/audio/`
3. Pronto — os players já apontam para esses caminhos

Se quiser mudar o nome que aparece abaixo de cada disco, edite os elementos
`<div class="vinyl-tooltip">` no `index.html`.

---

Feito com muito amor
