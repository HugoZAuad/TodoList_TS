# Lista de Tarefas com React, TypeScript e Vite

Este projeto é uma aplicação de lista de tarefas (To-Do List) desenvolvida com **React**, **TypeScript** e **Vite**. Ele permite adicionar, marcar como concluídas e remover tarefas, além de alternar entre os temas claro e escuro.

## Funcionalidades

- Adicionar novas tarefas.
- Marcar tarefas como concluídas.
- Remover tarefas.
- Persistência de tarefas no **LocalStorage**.
- Alternar entre os temas **claro** e **escuro**.

## Estrutura do Projeto

```
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.tsx
│   ├── main.tsx
│   ├── ThemeContext.tsx
│   └── vite-env.d.ts
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Tecnologias Utilizadas

- **React**: Biblioteca para construção de interfaces de usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Vite**: Ferramenta de build rápida para desenvolvimento web moderno.
- **ESLint**: Ferramenta de linting para manter a qualidade do código.

## Como Executar o Projeto

### Pré-requisitos

- **Node.js** (versão 16 ou superior)
- **npm** ou **yarn**

### Passos

1. Clone o repositório:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

4. Acesse a aplicação no navegador em: [http://localhost:5173](http://localhost:5173)

## Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Realiza o build da aplicação para produção.
- `npm run lint`: Executa o ESLint para verificar problemas no código.
- `npm run preview`: Visualiza o build de produção localmente.

## Estrutura de Código

### `App.tsx`

O componente principal da aplicação, responsável por gerenciar a lista de tarefas e a interação do usuário.

### `ThemeContext.tsx`

Gerencia o tema da aplicação (claro ou escuro) utilizando o **Context API** do React.

### `App.css`

Estilos da aplicação, incluindo suporte para os temas claro e escuro.

## Melhorias Futuras

- Adicionar suporte a múltiplos idiomas.
- Implementar testes unitários.
- Adicionar animações para transições de tema e tarefas.

## Licença

Este projeto é de uso livre e não possui uma licença específica.

---

Desenvolvido com ❤️ por Hugo Zeymer Auad.