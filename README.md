# Editor Mermaid

Editor web para criação e visualização de **diagramas de sequência Mermaid** em tempo real.

## Funcionalidades

- Edição de código Mermaid com renderização automática.
- Exemplo pronto para começar rapidamente.
- Cópia do código para a área de transferência.
- Download do diagrama em **SVG**.
- Alternância de tema no painel de preview.
- Persistência do conteúdo no `localStorage`.
- Redimensionamento entre painel de código e preview.

## Requisitos

- Node.js **18+**
- npm

## Instalação

```bash
npm install
```

## Como executar

```bash
npm start
```

Depois, abra no navegador:

```
http://localhost:3000
```

## Desenvolvimento

Também é possível executar com:

```bash
npm run dev
```

## Estrutura do projeto

```text
.
├── public/
│   ├── index.html
│   └── style.css
├── server.js
└── package.json
```

## Stack

- [Express](https://expressjs.com/)
- [Mermaid.js](https://mermaid.js.org/) (via CDN)

## Segurança básica

O servidor utiliza `express-rate-limit` para limitar requisições por IP.

## Licença

MIT
