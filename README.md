# EBAC_TALKS

> Contagem regressiva, landing committee, automatizando frontend

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://shields.io/)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://shields.io/)
![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow.svg)
![HTML](https://img.shields.io/badge/language-HTML-red.svg)
![CSS](https://img.shields.io/badge/language-CSS-blue.svg)

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Testing](#testing)

---

## Overview

Projeto de landing page com contagem regressiva para o evento utilizando JavaScript puro e animações CSS com **AOS**.

---

## Getting Started

### Prerequisites

- Navegador compatível
- Editor de código (Ex: VSCode)
- Node.js (opcional, caso queira rodar scripts de build)

### Installation

Clone este repositório:

```bash
git clone https://github.com/seu-usuario/ebac_talks.git
```

Navegue até o diretório do projeto:

```bash
cd ebac_talks
```

### Setup

Abra o arquivo `index.html` em seu navegador preferido para visualizar a landing page.

Para modificar o evento, altere a data dentro do arquivo:

```js
// src/scripts/main.js
const dataDoEvento = new Date("Dec 12, 2025 19:00:00");
```

### Usage

Acesse a landing page e acompanhe a contagem regressiva para o evento!

### Testing

Para testar se a contagem funciona, modifique a data do evento para uma data próxima à atual e veja o contador finalizar:

```js
const dataDoEvento = new Date("Jan 1, 2024 00:00:00");
```

---

## License

Este projeto está sob a licença MIT.
Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

