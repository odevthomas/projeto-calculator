# 🧮 Calculadora Web Responsiva – Thomas Eduardo

Projeto de calculadora responsiva e funcional desenvolvida com **HTML**, **CSS** e **JavaScript Puro**, com foco em:
- Lógica clara e modular;
- Interface moderna com Raleway + responsividade;
- Exibição de símbolos pressionados em tempo real;
- Operações matemáticas com formatação de resultado;
- Estrutura organizada para aprendizado e portfólio profissional.

---

## ✨ Demonstração

![Calculadora](./preview.jpg)

---

## 🚀 Tecnologias Usadas

- HTML5 semântico
- CSS3 com variáveis e responsividade
- JavaScript modular (sem frameworks)
- Google Fonts (Raleway)
- Organização de código por componentes lógicos

---

## 💡 Funcionalidades

- ✅ Soma, Subtração, Multiplicação e Divisão
- ✅ Cálculo de porcentagem
- ✅ Limpar (`C`) e Apagar (`⌫`)
- ✅ Formatação automática de resultados longos
- ✅ Histórico de símbolos pressionados exibido ao vivo
- ✅ Totalmente responsiva
- ✅ Sem dependências externas (zero libs)

---

## 📁 Estrutura de Código

```html
📦 calculator
 ┣ 📂 css
 ┃ ┗ 📜 styles.css        # Estilização completa e responsiva
 ┣ 📂 js
 ┃ ┗ 📜 script.js         # Toda a lógica da calculadora
 ┣ 📂 favicon             # Ícones para dispositivos e browsers
 ┣ 📜 index.html          # Estrutura principal da calculadora
 ┣ 📜 site.webmanifest    # Manifesto para PWA (opcional)
 ┗ 📜 README.md           # Documentação do projeto
````

---

## 🧪 Como Executar Localmente

```bash
# 1. Clone o repositório
git clone https://github.com/seuusuario/calculadora-thomas.git

# 2. Acesse a pasta
cd calculadora-thomas

# 3. Abra o arquivo index.html no navegador
```

---

## 📱 Responsividade

A calculadora se adapta bem em resoluções de celular, tablet e desktop. Isso foi possível usando `rem`, `flexbox` e media queries personalizadas.

---

## 🔍 SEO e Acessibilidade

* `lang="pt-br"` no HTML
* Meta tags para responsividade
* Tipografia legível (linha, peso, contraste)
* Sem `eval` direto exposto (uso seguro e encapsulado)

---

## 🧠 Lógica JavaScript

A lógica está centralizada no arquivo `js/script.js` e segue uma arquitetura simples:

* Um array central com todos os botões e seus tipos
* Um objeto `state` que guarda `operation`, `result`, `history`, `output`
* Separação por responsabilidades: `handleCalculatorInput`, `evaluateExpression`, `handleKey`, `updateAllDisplays`, etc.
* Resultado formatado com limite de casas decimais

---
