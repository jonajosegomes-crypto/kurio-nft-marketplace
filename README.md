# KURIO — NFT Marketplace

Projeto frontend inspirado nas oito telas do PDF de referência **KURIO NFT Marketplace — Telas da Aplicação**.

## Telas implementadas

1. **Página inicial / Banner principal** — hero da coleção em destaque, indicadores, categorias, busca, ordenação e cards de NFTs.
2. **Detalhes do NFT** — imagem, coleção, criador, preço, disponibilidade, blockchain e ações de compra.
3. **Carrinho** — lista de NFTs, remoção de itens, subtotal, taxa de serviço e total.
4. **Checkout / Pagamento** — dados do comprador, escolha entre carteira cripto e cartão e resumo do pedido.
5. **Confirmação** — tela de sucesso com identificador de pedido e resumo demonstrativo.
6. **Login** — modal de autenticação com e-mail, senha e opções visuais de login social.
7. **Cadastro** — modal de criação de conta com usuário, e-mail, senha e confirmação.
8. **Perfil / Carteira** — dados pessoais, foto, preferências e área para conectar carteira.

## Tecnologias

- React + TypeScript
- Vite
- CSS responsivo
- Lucide React para ícones
- localStorage para persistência local de carrinho, favoritos e sessão demonstrativa

## Como executar

Requisitos: Node.js 20 ou superior e npm.

```bash
npm install
npm run dev
```

Abra no navegador o endereço informado pelo Vite (normalmente `http://localhost:5173`).

Para gerar a versão de produção:

```bash
npm run build
npm run preview
```

## Funcionalidades demonstrativas

- Navegação entre as oito experiências descritas no PDF.
- Busca por nome/coleção, filtro por categoria e ordenação por preço.
- Favoritar NFTs e persistir favoritos no navegador.
- Adicionar e remover itens do carrinho, com cálculo de taxa e total.
- Fluxo de checkout e confirmação demonstrativa.
- Login/cadastro local e persistência do nome de usuário.
- Layout adaptável para desktop, tablet e celular.

## Limitações conhecidas

Este projeto é um protótipo frontend. Não há API/backend, autenticação real, processamento de pagamentos, conexão efetiva com MetaMask/WalletConnect, transações blockchain, sincronização em tempo real ou integração com serviços externos. Os botões de Google/Facebook e conexão de carteira são apenas elementos demonstrativos. Os dados e valores exibidos são fictícios. A imagem principal do Emerald Ape é um SVG local criado para o protótipo; algumas imagens secundárias usam URLs externas.

## Estrutura

```text
kurio-marketplace/
├── public/
│   └── ape.svg
├── src/
│   ├── App.tsx
│   ├── App.css
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── index.html
├── package.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
└── vite.config.ts
```
