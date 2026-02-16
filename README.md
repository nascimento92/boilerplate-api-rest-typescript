# TS API Boilerplate

Boilerplate de uma API REST em Node.js com TypeScript usando Express, pronta para desenvolvimento rápido.

## Tecnologias

- Node.js
- TypeScript
- Express
- CORS

## Requisitos

- Node.js 18+ instalado
- npm ou outro gerenciador de pacotes compatível

## Instalação

No diretório do projeto:

```bash
npm install
```

## Scripts disponíveis

- Desenvolvimento:

```bash
npm run dev
```

Sobe o servidor em modo desenvolvimento com recarregamento automático.

- Build:

```bash
npm run build
```

Compila o código TypeScript para JavaScript na pasta `dist`.

- Produção:

```bash
npm start
```

Executa a versão compilada em `dist/server.js`.

## Estrutura do projeto

- `src/server.ts`: ponto de entrada da API.
- `tsconfig.json`: configuração do compilador TypeScript.
- `package.json`: scripts, dependências e metadados do projeto.

## Endpoints

### Healthcheck

- Método: `GET`
- URL: `/health`
- Resposta:

```json
{
  "status": "ok"
}
```

## Variáveis de ambiente

- `PORT`: porta na qual o servidor será executado (padrão: `3000`).

Exemplo:

```bash
PORT=4000 npm run dev
```
