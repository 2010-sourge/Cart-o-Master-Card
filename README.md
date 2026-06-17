# 💳 Glassmorphism Credit Card UI — HTML & CSS

Um componente de **cartão de crédito** com efeito **Glassmorphism**, construído com **HTML e CSS puro**. O design moderno combina um fundo escuro com círculos de gradiente roxo e um cartão translúcido com efeito de vidro fosco.

---

## ✨ Preview

O projeto exibe:
- **Cartão de crédito** com efeito glassmorphism (vidro translúcido)
- **Logo Mastercard** com os círculos vermelho e laranja sobrepostos
- **Chip dourado** no canto superior direito
- **Número do cartão**, nome do titular e validade
- **Fundo escuro** com dois círculos decorativos em gradiente roxo/rosa

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura semântica do card
- **CSS3** — glassmorphism (`backdrop-filter`, `background: rgba`), gradientes, `border-radius` e `box-shadow`

---

## 📁 Estrutura do Projeto

```
credit-card-ui/
├── index.html
└── style.css
```

---

## 🚀 Como Executar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` no seu navegador

Nenhuma instalação ou dependência necessária!

---

## 🎨 Efeito Glassmorphism

O efeito de vidro é criado com as seguintes propriedades CSS:

```css
.card {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-radius: 16px;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
}
```

Os círculos de fundo em gradiente são essenciais para que o efeito de desfoque do glassmorphism seja visível.

---

## 🧩 Estrutura Visual

```
┌──────────────────────────────────────┐
│  🔴🟠 Master Card          [Chip 💳] │
│                                      │
│  Card Number                         │
│  8050  5040  2030  3020              │
│                                      │
│  Prem Kumar Shahi       Valid Thru   │
│                          05/28       │
└──────────────────────────────────────┘
      (sobre dois círculos roxos em gradiente)
```

---

## ⚙️ Personalização

| Elemento | Como alterar |
|---|---|
| Número do cartão | Edite o texto `.card-number` no HTML |
| Nome do titular | Altere o texto `.card-holder` |
| Data de validade | Edite o `.valid-thru` |
| Cor dos círculos | Altere o `background` dos `.circle` no CSS |
| Intensidade do blur | Ajuste o valor de `backdrop-filter: blur()` |

---

## 📌 Funcionalidades

- [x] Efeito Glassmorphism com `backdrop-filter`
- [x] Fundo escuro com círculos decorativos em gradiente
- [x] Logo Mastercard com círculos sobrepostos em CSS
- [x] Chip do cartão estilizado
- [x] Layout com Flexbox
- [x] 100% HTML e CSS — sem JavaScript

---

## 🌐 Compatibilidade

> ⚠️ O efeito `backdrop-filter` não é suportado em versões antigas do Firefox. Para melhor visualização, use **Chrome**, **Edge** ou **Safari**.

---

## 🎨 Inspiração

Projeto inspirado em tutoriais de **Glassmorphism UI** com HTML e CSS, demonstrando como criar interfaces modernas e elegantes sem bibliotecas externas.

---

## 📄 Licença

Este projeto é livre para uso educacional e pessoal.
