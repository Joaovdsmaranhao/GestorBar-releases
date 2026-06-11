<div align="center">

  <h1>GestorBar</h1>

  <p>
    <strong>Sistema POS completo para bares, restaurantes e eventos.</strong><br />
    Rápido, 100% offline e com app para garçons direto no celular.
  </p>

  <p>
    <a href="https://github.com/Joaovdsmaranhao/GestorBar-releases/releases">
      <img src="https://img.shields.io/badge/versão-2.6.4-2563eb?style=for-the-badge" alt="versão" />
    </a>
    <img src="https://img.shields.io/badge/plataforma-Windows%2010%2B-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="windows" />
    <img src="https://img.shields.io/badge/licença-proprietária-dc2626?style=for-the-badge" alt="licença" />
  </p>

  <p>
    <a href="#-funcionalidades">Funcionalidades</a> ·
    <a href="#-instalação">Instalação</a> ·
    <a href="#-app-para-garçons">App de Garçom</a> ·
    <a href="#-primeiros-passos">Começar</a> ·
    <a href="#-suporte">Suporte</a>
  </p>

  <br />


</div>

---

## ✨ Por que GestorBar?

O GestorBar foi feito pra quem **não pode parar a operação por causa da internet e para não depender de comanda de papel**.
ele tem um Sistema desktop nativo, dados locais e um app que os garçons abrem direto no celular pela Wi-Fi do estabelecimento — sem instalação, sem dependência de nuvem.

- ⚡ **100% offline** — opera mesmo sem internet
- 📱 **App de garçom em PWA** — funciona em qualquer celular, zero instalação
- 🖨️ **Impressão térmica nativa** — cupons e comandas saem direto
- 🔄 **Atualizações automáticas** — sempre na versão mais recente
- 🔐 **Multi-usuário com permissões** — Admin, Gerente, Caixa e Garçom
- 🎉 **Modo Evento** — venda avulsa pra shows, festas e festivais

---

## 🎯 Funcionalidades

### Operação
- **Gestão de comandas** — abertura, edição e fechamento por mesa
- **Controle de caixa** — abertura e fechamento com relatórios de turno
- **Modo Evento** — venda avulsa para eventos e shows, com controle separado
- **Pagamentos** — dinheiro, cartão, PIX e divisão de conta com cálculo de troco
- **Descontos e taxas** — percentual ou valor fixo + taxa de serviço

### Cardápio & Cozinha
- **Cardápio digital** — produtos organizados por categoria e preço
- **Impressão térmica** — cupons e comandas direto para impressora

### Time
- **App para garçons (PWA)** — acesso pelo celular via Wi-Fi
- **Controle de acesso (RBAC)** — perfis Admin, Gerente, Caixa e Garçom
- **Tela de bloqueio** — trava por inatividade com desbloqueio por senha

### Gestão
- **Relatórios de vendas** — exportáveis para Excel
- **Atualizações automáticas** — notificação e instalação em 1 clique

---

## 📥 Instalação

### Requisitos

| Item | Mínimo | Recomendado |
|---|---|---|
| **Sistema** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 4 GB | 8 GB |
| **Disco** | 500 MB | 1 GB livre |
| **Impressora** | — | Térmica compatível |

### Passo a passo

1. Acesse a página de [**Releases**](https://github.com/Joaovdsmaranhao/GestorBar-releases/releases)
2. Baixe o arquivo `GestorBar_Setup_x.x.x.exe` da versão mais recente
3. Execute o instalador **como Administrador**
4. Siga as instruções na tela
5. Abra o GestorBar pelo atalho criado na área de trabalho

> [!NOTE]
> O instalador pede permissão de administrador para configurar as regras de firewall que liberam o app dos garçons na rede local.

---

## 📱 App para Garçons

O GestorBar inclui um app web progressivo (PWA) que os garçons acessam pelo Wi-Fi do estabelecimento — **sem instalar nada no celular**.

### Como conectar

1. Celular/tablet e computador conectados na **mesma rede Wi-Fi**
2. No GestorBar (desktop), abra **Configurações** e copie o endereço de IP exibido
3. No celular, acesse `http://[IP]:3000` em qualquer navegador
4. Faça login com seu usuário e comece a usar

> [!TIP]
> Adicione à tela inicial do celular pra abrir como um app nativo. Compatível com Chrome, Safari e Firefox.

---

## 🚀 Primeiros Passos

Ao abrir o GestorBar pela primeira vez:

1. **Crie o usuário administrador** — nome, usuário e senha
2. **Configure o estabelecimento** — dados do local em **Configurações**
3. **Cadastre os produtos** — itens do cardápio em **Produtos**
4. **Abra o caixa** — antes de qualquer venda, abra o caixa em **Caixa**
5. **Comece a vender** — crie comandas ou venda direto

---

## 🔄 Atualizações

O GestorBar verifica automaticamente novas versões ao iniciar. Quando uma atualização estiver disponível, clique em **Atualizar agora** e pronto.

Para atualizar manualmente, baixe o instalador mais recente em [Releases](https://github.com/Joaovdsmaranhao/GestorBar-releases/releases) e execute normalmente. **Todos os dados são preservados.**

---

## 💬 Suporte

Achou um bug ou tem uma sugestão? Abra uma issue:

- 🐛 [**Reportar um problema**](https://github.com/Joaovdsmaranhao/GestorBar-releases/issues/new)
- 💡 [**Sugerir funcionalidade**](https://github.com/Joaovdsmaranhao/GestorBar-releases/issues/new)
- 📚 [**Ver todas as issues**](https://github.com/Joaovdsmaranhao/GestorBar-releases/issues)

Inclua o máximo de detalhes possível, principalmente a **versão do sistema** (visível em **Configurações → Sobre**) e prints/passos para reproduzir.

---

## 📜 Licença

GestorBar é um software **proprietário**. O uso é condicionado à aquisição de uma licença válida. Distribuição, cópia ou modificação não autorizada é proibida.

---

<div align="center">

  **Desenvolvido por [Otto Stack](https://github.com/Joaovdsmaranhao)**

  <sub>v2.6.4 · GestorBar © 2026 — Todos os direitos reservados</sub>

</div>
