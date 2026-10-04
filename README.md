# Calculadora de IMC

Aplicação web desenvolvida como atividade prática para exercitar **HTML, CSS e JavaScript**. O sistema recebe altura e peso, calcula o IMC e apresenta sua classificação.

## Objetivo

Praticar fundamentos de desenvolvimento web, manipulação do DOM, eventos e implementação de uma regra de negócio no front-end.

## O que o projeto faz

- Recebe altura em centímetros e peso em quilogramas.
- Converte a altura para metros.
- Calcula o IMC pela fórmula `peso / altura²`.
- Exibe o resultado com duas casas decimais.
- Classifica o resultado como abaixo do peso, peso normal, sobrepeso ou obeso.

## Tecnologias

- **HTML5** — estrutura da aplicação.
- **CSS3** — estilização da interface.
- **JavaScript** — lógica, cálculo e manipulação do DOM.

## Arquitetura

Aplicação front-end simples e estática, sem backend ou banco de dados:

```text
index.html
    │
    ├── style.css
    │
    └── script.js
```

## Modelagem

Não existe modelagem de banco de dados. O domínio é representado pelos dados informados no formulário:

```text
Altura + Peso
      │
      ▼
    Cálculo
      │
      ▼
 IMC + Classificação
```

## Como clonar

```bash
git clone https://github.com/NickFernands/atv2-labweb.git
cd atv2-labweb
```

## Como executar

Não há dependências ou build. Abra o arquivo `index.html` no navegador.

Durante o desenvolvimento, também é possível utilizar o **Live Server** do VS Code.

## Autor

**Nicholas Fernandes**
