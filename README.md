# Blog Simples com Vue 3 + Vite

Este projeto é um blog simples desenvolvido com [Vue 3](https://vuejs.org/) e [Vite](https://vitejs.dev/), utilizando Vue Router para navegação entre páginas e componentes dinâmicos. O objetivo é demonstrar a estrutura básica de uma SPA (Single Page Application) com Vue, incluindo carregamento assíncrono de componentes e organização modular.

## Funcionalidades

- Listagem de posts na página inicial
- Visualização de post individual por rota dinâmica (`/post/:slug`)
- Carregamento assíncrono de componentes com feedback de loading e erro
- Componentes reutilizáveis para exibição de posts, loading e erros

## Estrutura do Projeto

```bash
src/
├── components/       # Componentes reutilizáveis
├── views/            # Páginas da aplicação
├── router/          # Configuração do Vue Router
├── store/           # Gerenciamento de estado (opcional)
├── assets/          # Imagens e outros arquivos estáticos
└── App.vue          # Componente raiz
main.js              # Entrada da aplicação
```

## Instalação e Execução

Para rodar este projeto, você precisa ter o [Node.js](https://nodejs.org/) instalado. Em seguida, execute os seguintes comandos:

```bash
# Clone este repositório
git clone https://github.com/seuusuario/seurepositorio.git

# Acesse a pasta do projeto
cd seurepositorio

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

Acesse `http://localhost:3000` no seu navegador para ver o projeto em funcionamento.

## Considerações Finais

Este é um projeto de exemplo para fins educacionais. Sinta-se à vontade para explorar, modificar e aprimorar conforme necessário. Para mais informações sobre Vue 3 e Vite, consulte a documentação oficial do [Vue.js](https://vuejs.org/) e do [Vite](https://vitejs.dev/).
