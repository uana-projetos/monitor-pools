<div align="center">

# 🧠 DefiMind

**Monitor de portfólio DeFi em tempo real — construído para traders e farmers brasileiros**

[![Live App](https://img.shields.io/badge/▶%20Abrir%20App-DefiMind-00d4ff?style=for-the-badge&logo=github)](https://uana-projetos.github.io/defimind/)
[![Version](https://img.shields.io/badge/versão-v1.8.0-blueviolet?style=for-the-badge)](https://uana-projetos.github.io/defimind/)
[![PWA](https://img.shields.io/badge/PWA-instalável-34d399?style=for-the-badge)](https://uana-projetos.github.io/defimind/)

</div>

---

## 🚀 O que é o DefiMind?

Um dashboard completo, single-file, sem backend e sem custódia — rode direto no navegador ou instale como app (PWA). Dados reais via **DefiLlama API**, carteiras read-only, rastreador de airdrops e muito mais.

---

## ✨ Funcionalidades

### 💰 Yield — RWA & Stablecoins
- APY ao vivo de pools de RWA (Ondo, Backed, Maple, TrueFi)
- Stablecoins em Ethereum, Arbitrum, Base, Solana
- Filtro por cadeia e APY mínimo
- **Botão "Live DefiLlama"** — busca os 30 melhores yields do mercado em tempo real

### 🌊 Pools — ETH, BTC, SOL, Índices, Ações, Metais
- Cobertura: Uniswap v3/v4, Orca, Raydium, Camelot, Aerodrome, Kamino, xStocks, Ondo, Trade[XYZ]
- **Pools de índices reais**: S&P 500 e Nasdaq via xStocks (Kraken/Backed), Ondo Finance e Trade[XYZ] no Hyperliquid (licença oficial S&P 500)
- Busca instantânea + filtro por rede
- Carteiras conectadas exibem saldo + links para explorers

### 🪂 Airdrops — Projetos ativos com maior potencial
| Projeto | Chain | Status | Est. Valor |
|---------|-------|--------|------------|
| Meteora S2 | Solana | 🟢 Live | $200–$2,000 |
| Axiom | Solana / Hyperliquid | 🔥 Hot | $500–$5,000 |
| xStocks xPoints | Solana | 🟢 Live | $300–$3,000 |
| Kamino XP | Solana | 🟢 Live | $100–$2,500 |
| Lighter | Hyperliquid | 🔥 Hot | $1,000–$8,000 |
| Drift | Solana | 🆕 Novo | $200–$1,500 |
| Aerodrome S2 | Base | 🟢 Live | $150–$2,000 |
| Hyperflow | Hyperliquid | 🆕 Novo | $300–$4,000 |

Cada projeto tem checklist de tarefas + barra de progresso pessoal salva no browser.

### 💸 Empréstimos DeFi
- Taxas de borrow/supply ao vivo de Aave, Compound, Kamino, Drift, MarginFi
- Cálculo de Health Factor em tempo real
- Alertas automáticos de risco de liquidação (HF < 1.5)
- **Botão "Taxas ao Vivo"** — puxa dados reais da DefiLlama

### 👛 Carteira Read-Only (sem chave privada)
- Conecta endereços EVM e Solana por endereço público
- Exibe saldo ao vivo (ETH via publicnode, SOL via mainnet RPC)
- Links diretos: DefiLlama Portfolio, Zapper, DeBank, Etherscan

---

## ⚡ Dados ao vivo vs estáticos

| Dado | Atualização |
|------|-------------|
| Saldo de carteiras | ✅ Ao vivo a cada visita |
| Botão "Live DefiLlama" | ✅ Ao vivo (cache 5min) |
| Pools e APYs fixos | 📋 Curadoria manual por versão |
| Lista de airdrops | 📋 Atualizado a cada deploy |

---

## 🛠️ Tech Stack

- **Single HTML file** — zero backend, zero dependências de servidor
- **Service Worker / PWA** — funciona offline, instalável na tela inicial
- **DefiLlama Yields API** — `yields.llama.fi/pools` e `yields.llama.fi/lendBorrow`
- **Public RPC** — `ethereum.publicnode.com` + `api.mainnet-beta.solana.com`
- **localStorage** — persistência de pools, empréstimos, carteiras e progresso de airdrops

---

## 📲 Instalar como App (PWA)

1. Abra **https://uana-projetos.github.io/defimind/** no celular ou desktop
2. No celular: toque em **"Compartilhar → Adicionar à Tela Inicial"**
3. No desktop Chrome: clique no ícone de instalação na barra de endereço

---

## 📣 Atualizações automáticas

Ao publicar uma nova versão, quem já tem o app instalado recebe um banner **"🚀 Atualização disponível"** e atualiza com 1 clique — sem precisar reinstalar.

---

## ⚠️ Aviso Legal

Este painel é **informativo**. Não constitui recomendação financeira. Verifique sempre os riscos de impermanent loss e liquidação antes de alocar capital em protocolos DeFi.

---

<div align="center">

Desenvolvido com ❤️ para a comunidade DeFi brasileira por **Uaná Lee**

[![App ao vivo](https://img.shields.io/badge/▶%20defimind.app-00d4ff?style=flat-square)](https://uana-projetos.github.io/defimind/)

</div>
