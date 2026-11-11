# ✝️ Santos: História e Oração

Site que apresenta a vida, os testemunhos de fé e as orações de santos e mártires da Igreja Católica, intercessores que nos aproximam de Deus no caminho da conversão e da oração diária.

🔗 **Acesse o site:** [jordana-code.github.io/Historia-e-Oracao-dos-Santos](https://jordana-code.github.io/Historia-e-Oracao-dos-Santos/)

---

##  Sobre o projeto

Cada santo aparece em um card com sua imagem, a data da festa, os títulos e patronatos, a história de vida e o significado dos símbolos da imagem. A oração de cada santo também faz parte do card:

- **No computador:** ao passar o mouse sobre o card, a história dá lugar à oração.
- **No celular e no tablet:** como não existe "passar o mouse" em telas touch, a história e a oração aparecem juntas, uma embaixo da outra.

## 🙏 Santos apresentados

- Santa Teresa d'Ávila
- Santa Bárbara
- São Jorge
- São Tarcísio
- São João Batista
- Santa Maria Goretti
- São José
- São Pio de Pietrelcina (Padre Pio)
- Sagrada Família
- Santo Antônio
- São Francisco de Assis

## Tecnologias utilizadas

- **HTML5**
- **CSS3**: Flexbox, media queries e `clamp()` para tamanhos fluidos
- **Google Fonts**: Lora (textos) e Lobster (títulos)
- **GitHub Pages** para a hospedagem

## Responsividade

O layout se adapta a celulares, tablets e computadores:

- Os tamanhos de fonte, a altura do banner e os espaçamentos se ajustam à largura da tela com `clamp()`.
- Em telas de até **640px**, os cards passam a ser exibidos em coluna, com a imagem acima do texto.
- Em dispositivos sem mouse (`@media (hover: none)`), a oração fica sempre visível, logo abaixo da história.

## Estrutura de pastas

```
Historia-e-Oracao-dos-Santos/
├── index.html    # Página principal com os cards dos santos
├── style.css     # Estilos e regras de responsividade
└── img/          # Imagens dos santos, do banner e o ícone da aba
```



## 👩‍💻 Autora

Desenvolvido por **Jordana Moreira**.

[![GitHub](https://img.shields.io/badge/GitHub-jordana--code-181717?logo=github)](https://github.com/jordana-code)
