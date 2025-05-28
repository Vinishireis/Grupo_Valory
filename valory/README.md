# Projeto Grupo Valory – React + Vite

Este projeto é o site institucional do **Grupo Valory**, desenvolvido com **React** e **Vite**, visando alta performance, facilidade de manutenção e uma excelente experiência para o usuário.

## 🚀 Tecnologias Utilizadas

* **React** – Biblioteca para criação de interfaces modernas e reativas.
* **Vite** – Ferramenta de build rápida, com suporte a HMR (Hot Module Replacement).
* **ESLint** – Para manter o código limpo e padronizado.
* **Babel** ou **SWC** – Plugins disponíveis para Fast Refresh.

## 📁 Estrutura do Projeto

```bash
├── public/         # Arquivos públicos
├── src/            # Código-fonte do projeto
│   ├── assets/     # Imagens e recursos estáticos
│   ├── components/ # Componentes reutilizáveis
│   ├── pages/      # Páginas do site
│   └── App.jsx     # Componente principal
├── index.html      # Estrutura base do app
├── vite.config.js  # Configuração do Vite
└── package.json    # Dependências e scripts
```

## 🔍 ESLint e Qualidade de Código

O projeto já vem com configurações básicas de ESLint. Para ambientes de produção, recomenda-se:

* Migrar para **TypeScript**
* Usar regras de lint com checagem de tipo com [`typescript-eslint`](https://typescript-eslint.io)

Exemplo de template com TypeScript:
👉 [Vite + React + TypeScript Template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts)

## 🛠️ Instalação e Uso

```bash
# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

A aplicação estará disponível em: [http://localhost:5173](http://localhost:5173)

## 📦 Build para Produção

```bash
npm run build
```

Os arquivos otimizados serão gerados na pasta `dist/`.

## 🤝 Sobre o Grupo Valory

O **Grupo Valory** é referência em soluções financeiras com foco em transformar dívidas em oportunidades, com transparência e compromisso. Este projeto digital é uma extensão da nossa missão: oferecer atendimento confiável e acessível para todos.

---

