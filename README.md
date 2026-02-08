<div align="center">

# 🔥 LOFYGANG Discord Tools

```
██╗      ██████╗ ███████╗██╗   ██╗ ██████╗  █████╗ ███╗   ██╗ ██████╗    
██║     ██╔═══██╗██╔════╝╚██╗ ██╔╝██╔════╝ ██╔══██╗████╗  ██║██╔════╝   
██║     ██║   ██║█████╗   ╚████╔╝ ██║  ███╗███████║██╔██╗ ██║██║  ███╗  
██║     ██║   ██║██╔══╝    ╚██╔╝  ██║   ██║██╔══██║██║╚██╗██║██║   ██║ 
███████╗╚██████╔╝██║        ██║   ╚██████╔╝██║  ██║██║ ╚████║╚██████╔╝    
╚══════╝ ╚═════╝ ╚═╝        ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝        
```

### Ferramenta completa de automação para Discord

[![Node.js](https://img.shields.io/badge/Node.js-16+-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![License](https://img.shields.io/badge/license-ISC-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()

</div>

---

## 🎯 Sobre

Uma ferramenta poderosa e completa desenvolvida em Node.js para automação no Discord. Interface CLI colorida e intuitiva com 15+ funcionalidades para gerenciar mensagens, clonar servidores, controlar canais de voz e muito mais.

---

## ✨ Funcionalidades

### 🧹 Limpeza e Gerenciamento
- **Clear DM** - Limpa mensagens em DMs específicas
- **Clear DM's** - Remove todas as conversas abertas
- **Clear DM Friends** - Limpa apenas DMs com amigos
- **Clear Content** - Remove mensagens em canais específicos
- **Delete DMs** - Deleta todas as conversas privadas

### 👥 Gerenciamento Social
- **Clear Friends** - Remove todos os amigos da lista
- **Clear Servers** - Sai de todos os servidores
- **WhiteList** - Protege usuários e servidores importantes

### 🔧 Utilidades Avançadas
- **Server Cloner** - Clona servidores completos (roles, canais, emojis)
- **Join Voice** - Entra e mantém presença em canais de voz
- **Trigger** - Sistema automático de limpeza por comando
- **Utilidades em Call** - Ferramentas para chamadas de voz
- **Utilidades em Chat** - Ferramentas para mensagens de texto

### 🏠 Personalização
- **Add/Remove Hypesquad** - Gerencia badges do perfil
- **Configurações** - Personaliza comportamento da ferramenta

---

## 🚀 Instalação Rápida

### Pré-requisitos
- [Node.js](https://nodejs.org/) versão 16 ou superior
- Token de conta Discord

### Comandos
```bash
# Clone o repositório
git clone https://github.com/dwagwa617-wq/Discord-MultiTools-Lofy.git
cd Discord-MultiTools-Lofy

# Instale as dependências
npm install

# Execute o programa
npm start
```

---

## 💻 Como Usar

1. Execute o programa com `npm start`
2. Insira seu **token do Discord** quando solicitado
3. Escolha uma opção do menu principal:

```
┌────────────────────────────────────┐
│ MENU                               │
├────────────────────────────────────┤
│ 1  - Clear DM                      │
│ 2  - Clear DM's                    │
│ 3  - Clear DM Friends              │
│ 4  - Clear Content                 │
│ 5  - Server Cloner                 │
│ 6  - Trigger                       │
│ 7  - Clear Friends                 │
│ 8  - Clear Servers                 │
│ 9  - Delete DMs                    │
│ 10 - WhiteList                     │
│ 11 - Utilidades em Call            │
│ 12 - Utilidades em Chat            │
│ 13 - Join Voice                    │
│ 14 - Add Hypesquad                 │
│ 15 - Remove Hypesquad              │
│ 99 - Configurações                 │
│ 0  - Sair                          │
└────────────────────────────────────┘
```

---

## 📖 Guia Detalhado

### 🔑 Como obter seu Token

1. Abra o Discord no navegador ([discord.com/app](https://discord.com/app))
2. Pressione `F12` para abrir as Ferramentas de Desenvolvedor
3. Vá para a aba **Console**
4. Cole este código e pressione Enter:

```javascript
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    if (!req.c) return;
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cToken copiado!', 'font-size: 50px');
```

5. Seu token será copiado automaticamente

> ⚠️ **NUNCA compartilhe seu token com ninguém!**

---

### 🆔 Como obter IDs

1. Discord → Configurações → Avançado → Modo Desenvolvedor ✅
2. Clique direito no avatar/servidor/canal → `Copiar ID`

---

## 🔧 Tecnologias

- **[Node.js](https://nodejs.org/)** - Runtime JavaScript
- **[discord.js-selfbot-v13](https://github.com/aiko-chan-ai/discord.js-selfbot-v13)** - Biblioteca Discord selfbot
- **[got](https://github.com/sindresorhus/got)** - Cliente HTTP
- **[chalk](https://github.com/chalk/chalk)** - Estilização de terminal
- **[@discordjs/voice](https://github.com/discordjs/voice)** - Suporte a canais de voz
- **[selfbot-lofy](https://www.npmjs.com/package/selfbot-lofy)** - Utilitários selfbot

---

## ⚠️ Aviso Legal

> **Este projeto utiliza selfbots, o que viola os Termos de Serviço do Discord.**  
> Pode resultar em banimento permanente. Use por sua conta e risco.  
> Apenas para fins educacionais.

---

## 📄 Licença & Autor

**Licença:** ISC  
**Desenvolvido por:** LOFYGANG

<div align="center">

⚠️ **Use com responsabilidade** ⚠️

</div>
