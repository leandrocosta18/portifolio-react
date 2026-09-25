# Portfólio - Leandro Oliveira Costa

Portfólio pessoal desenvolvido para apresentar minha trajetória, minhas habilidades e projetos práticos como desenvolvedor em formação.

O projeto está disponível em:

**[leandrocosta18.github.io/portifolio-react](https://leandrocosta18.github.io/portifolio-react/)**

## Sobre o projeto

Esta aplicação reúne informações sobre minha formação em Análise e Desenvolvimento de Sistemas, tecnologias que estudo e projetos que desenvolvi para praticar desenvolvimento frontend, integração com APIs e construção de interfaces responsivas.

O objetivo é evoluir continuamente o portfólio junto com minha experiência profissional e técnica.

## Tecnologias

- React 19
- TypeScript
- Vite
- Tailwind CSS v4
- Lucide React
- HTML, CSS e JavaScript
- Git e GitHub

## Funcionalidades

- Apresentação profissional e seção sobre mim
- Lista de linguagens, frameworks e ferramentas
- Cards com links para projetos publicados
- Links para GitHub, LinkedIn e e-mail
- Layout responsivo para desktop e dispositivos móveis
- Deploy automático no GitHub Pages através do GitHub Actions

## Projetos apresentados

| Projeto | Link |
| --- | --- |
| Clima | [Acessar projeto](https://leandrocosta18.github.io/clima/) |
| Projeto de Login | [Acessar projeto](https://leandrocosta18.github.io/Projeto-de-Login/) |
| Site de Pizza | [Acessar projeto](https://leandrocosta18.github.io/projeto-site-pizza/) |
| Relógio | [Acessar projeto](https://leandrocosta18.github.io/projeto-relogio/) |
| Chat offline | [Ver no GitHub](https://github.com/leandrocosta18/react-chat-offline) |

## Como executar localmente

### Pré-requisitos

- Node.js 20 ou superior
- npm

### Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/leandrocosta18/portifolio-react.git
cd portifolio-react
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O projeto ficará disponível no endereço exibido pelo Vite, normalmente `http://localhost:5173`.

## Scripts disponíveis

| Comando | Descrição |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a versão de produção em `dist/` |
| `npm run lint` | Executa o Oxlint |
| `npm run preview` | Visualiza localmente o build de produção |

## Deploy

O workflow em [.github/workflows/deploy.yml](.github/workflows/deploy.yml) é executado automaticamente sempre que um commit é enviado para a branch `main`.

O processo:

1. Instala as dependências com `npm ci`.
2. Executa o build com `npm run build`.
3. Publica a pasta `dist/` no GitHub Pages.

Para o deploy funcionar, a configuração de Pages do repositório deve usar **GitHub Actions** como fonte de publicação.

## Contato

- E-mail: [leandrooliveiracosta2001@gmail.com](mailto:leandrooliveiracosta2001@gmail.com)
- LinkedIn: [Leandro Oliveira Costa](https://www.linkedin.com/in/leandro-oliveira-128516284)
- GitHub: [@leandrocosta18](https://github.com/leandrocosta18)

## Licença

Este projeto é de uso pessoal e funciona como apresentação do meu trabalho e dos meus estudos.
