# Ford — aplicação Angular

**Interface online:** https://programmergv.github.io/Ford/

A publicação usa GitHub Pages e rotas com fragmento (`#/home`, `#/dashboard`) para funcionar em hospedagem estática. A tela de login é um protótipo visual; home e dashboard ainda são esboços de componentes. Não é necessário fornecer credenciais reais para visualizar a interface.

Projeto de interface web com Angular 19 e Bootstrap 5. O código organiza três páginas carregadas por rota: login (`/`), home (`/home`) e dashboard (`/dashboard`).

## Executar

Requer Node.js e npm compatíveis com Angular 19.

```bash
npm ci
npm start
```

Abra `http://localhost:4200`. Para gerar o build, execute `npm run build`. O comando `npm test` executa a suíte configurada com Jasmine e Karma.

## Organização

- `src/app/pages/`: componentes e templates de login, home e dashboard.
- `src/app/app.routes.ts`: rotas com carregamento dos componentes.
- `src/styles.css`: estilos globais.

## Limites da versão

É um projeto de interface. A existência de uma página de login não demonstra autenticação real. Na versão inspecionada para esta documentação, os componentes das três páginas não contêm lógica de integração com backend. Não são alegados API, persistência ou autorização implementadas.

Esta revisão descreve o código existente; não altera funcionalidades nem declara que o build foi executado nesta revisão de documentação.

Desenvolvido por [Gabriel Vinicius](https://github.com/ProgrammerGV). Outro projeto: [Edital Inteligente](https://github.com/ProgrammerGV/edital-inteligente), com busca em PDFs, avaliação e fontes por página.
