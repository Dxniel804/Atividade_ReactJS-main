# Site Univille - Atividade React/Next.js

Este é um projeto de atividade acadêmica que consiste no desenvolvimento de um site institucional para a Univille, baseado em um design Figma fornecido pelo professor. O projeto foi desenvolvido utilizando Next.js, TypeScript e Tailwind CSS, seguindo os princípios e conceitos estudados em sala de aula.

## 🎯 Objetivo da Atividade

Desenvolver uma página web aplicando os conceitos estudados em sala de aula, com foco em:

- **Aplicação de conceitos**: Utilizar os conhecimentos adquiridos para criar uma interface funcional e moderna
- **Estrutura de layout bem definida**: Organizar o conteúdo de forma lógica e visualmente atrativa
- **Componentização**: Dividir a interface em componentes reutilizáveis para melhor manutenção e escalabilidade
- **Organização de rotas**: Estruturar as rotas da aplicação de forma lógica e consistente

## 🚀 Funcionalidades

- **Página Inicial**: Hero section, estatísticas, sobre a universidade, preview de cursos e depoimentos
- **Página de Cursos**: Lista completa de cursos com funcionalidade de busca e redirecionamento
- **Página de Curso Específico**: Detalhes completos do curso de Publicidade e Propaganda
- **Design Responsivo**: Adaptado para desktop, tablet e mobile
- **Componentes Reutilizáveis**: Header, Footer, seções compartilhadas e layout consistente
- **Navegação Intuitiva**: Sistema de navegação com scroll para seções específicas

## 📚 Princípios Aplicados

Durante o desenvolvimento deste projeto, foram seguidos os seguintes princípios estudados em sala de aula:

- **Aplicação de conceitos estudados**: Utilização prática dos conhecimentos adquiridos sobre React, Next.js, TypeScript e Tailwind CSS
- **Estrutura de layout bem definida**: Organização clara e hierárquica dos componentes e seções da página
- **Componentização dos elementos**: Divisão da interface em componentes reutilizáveis (Header, Footer, HeroSection, etc.) para facilitar a manutenção
- **Organização de rotas**: Estruturação lógica das rotas da aplicação seguindo o App Router do Next.js

## ️ Tecnologias Utilizadas

- **Next.js 14** - Framework React
- **TypeScript** - Tipagem estática
- **Tailwind CSS** - Framework CSS utilitário
- **React 18** - Biblioteca de interface

## 📦 Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd site_nextJS
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## 📁 Estrutura do Projeto

```
src/
├── app/                    # App Router do Next.js
│   ├── cursos/            # Página de cursos
│   ├── layout.tsx         # Layout principal
│   └── page.tsx           # Página inicial
├── components/            # Componentes reutilizáveis
│   ├── Header.tsx         # Cabeçalho da aplicação
│   ├── Footer.tsx         # Rodapé da aplicação
│   └── InfoSection.tsx    # Seção de informações
└── styles/
    └── globals.css        # Estilos globais
```

## 🎨 Personalização

### Cores
As cores principais estão definidas no `tailwind.config.js`:
- `univille-green`: #1B5E20
- `univille-dark`: #0D1117
- `univille-gray`: #161B22

### Imagens
Adicione as imagens necessárias na pasta `public/images/` conforme descrito no arquivo `public/images/README.md`.

## 📱 Páginas

### Página Inicial (/)
- Hero section com call-to-action
- Estatísticas da universidade
- Seção "Sobre a Univille"
- Preview dos cursos
- Depoimentos de alunos
- Seção para receber informações

### Página de Cursos (/cursos)
- Hero section específico
- Barra de pesquisa
- Grid de cursos com filtro
- Seção para receber informações

## 🚀 Deploy

Para fazer o deploy em produção:

```bash
npm run build
npm start
```

## 📄 Scripts Disponíveis

- `npm run dev` - Executa o projeto em modo de desenvolvimento
- `npm run build` - Cria a versão de produção
- `npm start` - Executa a versão de produção
- `npm run lint` - Executa o linter

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.# Atividade_ReactJS

