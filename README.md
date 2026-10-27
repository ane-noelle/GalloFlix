# GalloFlix Angular 22

Projeto standalone construído a partir das 18 etapas do tutorial fornecido.

## 1. Requisitos

- Node.js 24.15.0 (ou uma versão aceita por `package.json`: `^22.22.3 || ^24.15.0 || >=26.0.0`)
- npm
- Angular CLI 22.2.1 (opcional globalmente, pois os scripts npm usam a versão local)
- Token **API Read Access Token (Bearer)** do TMDB

## 2. Instalação

```bash
cd galloflix
npm install
```

## 3. Token do TMDB

Abra `src/environments/environment.ts` e substitua somente o placeholder:

```ts
tmdbToken: '<COLE_SEU_TOKEN_BEARER_TMDB_AQUI>',
```

Não publique seu token em repositórios públicos. Neste exercício o token fica no frontend e pode ser visualizado no bundle e nas requisições.

## 4. Imagens

Adicione os sete arquivos listados em `public/img/ASSETS_NECESSARIOS.txt` na pasta `public/img/`, preservando exatamente os nomes.

## 5. Executar

```bash
npm start
```

Acesse `http://localhost:4200`.

## 6. Build

```bash
npm run build
```

A saída de produção será criada em `dist/galloflix`.
