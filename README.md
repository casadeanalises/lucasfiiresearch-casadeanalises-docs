<div align="center">
<!--   <img src="./docs/lucasfii_banner_logo.png" alt="CasaDeAnálises Banner" width="100%" /> -->

# LucasFII Research - CasaDeAnálises 📊

Bem-vindo ao **Lucas FII Research**! 

Saiba mais sobre os sistemas do LucasFII Research.

# Overview

Atualmente, o LucasFII Research possui os seguintes sistemas:

- Ambientes:
  - Development: https://dev-lucasfiiresearch-casadeanalises.vercel.app
  - Staging: https://staging-lucasfiiresearch-casadeanalises.vercel.app
  - Preprod: https://www.lucasfiiresearch.dev.br
  - Main/Prod: https://www.lucasfiiresearch.com.br

# Ambientes

Todos os sistemas são compostos de três ambientes:

- Production/main:
  - Sendo o principal ambiente, é utilizado por todas as pessoas para interagir com o sistema oficial!
- Staging:
  - Antes de entrar para production, as modificações passam pelo ambiente de staging para terem uma validação ou aprovação final.
- Development:
  - Quando novas funcionalidades ficam prontas e são revisadas individualmente, elas ficam no ambiente de development antes de entrarem para o ambiente de staging. Assim, é possível detectar problemas mais rapidamente, antes deles entrarem para o ambiente de production.
 
- # 📌 Padrão de Versionamento e Status 

Este documento define como as versões devem ser nomeadas e documentadas para manter a organização entre o desenvolvimento (Year 2) e a produção.

## 🏷️ Estrutura da Versão (SemVer + Time Tag)
Seguimos o padrão **v[Major].[Minor].[Patch]** acompanhado do ciclo temporal.

- **Major (1.x.x):** Grandes mudanças, reformulações ou troca de ano de projeto.
- **Minor (x.24.x):** Novas funcionalidades ou pacotes de melhoria.
- **Patch (x.x.7):** Correções de bugs e ajustes finos.

---

## 📅 Referência Temporal (Ciclo de Vida)
Como o projeto iniciou em **2025**, utilizamos a tag de ciclo para controle interno:
- **Y1 (Year 1):** 2025
- **Y2 (Year 2):** 2026 (Ciclo Atual)
- **M[1-12]:** Mês referente ao desenvolvimento.

*Exemplo de título de Issue/Release:* `v1.25.2 [Y2M1] - Update de Dashboard`

---

## 🚦 Categorias de Alteração (Labels)
Ao descrever as mudanças, utilize os seguintes prefixos para clareza:

| Prefixo | Tipo de Alteração | Descrição |
| :--- | :--- | :--- |
| `[NEW]` | Feature | Novas funcionalidades adicionadas. |
| `[IMP]` | Improvement | Melhorias em algo que já existe (Performance/UI). |
| `[FIX]` | Patch/Fix | Correção de erros ou bugs. |
| `[SEC]` | Security | Atualizações de segurança e pacotes. |

---

## 📝 Modelo de Registro (Template para Issue)

### Versão: `v1.24.7`
**Status:** 🟢 Estável / 🟡 Em Teste / 🔵 Em Desenvolvimento
**Ciclo:** `Y2M1` (Janeiro 2026)

### 🚀 O que há de novo?
- `[NEW]` Implementação do filtro de data no Gerenciador de Despesas.
- `[IMP]` Melhoria na velocidade de carregamento da lista de clientes em 30%.

### 🛠️ Correções (Patches)
- `[FIX]` Ajuste no erro de arredondamento de centavos no meio de pagamento.
- `[FIX]` Correção de layout quebrado em telas mobile (iPhone SE).

### ⚠️ Notas Técnicas
- Atualizada a biblioteca React Native para a versão X.
- Necessário rodar `npm install` após o pull.

# Repositórios

Todos os projetos do LucasFII Research estão hospedados no GitHub, distribuídos nos seguintes repositórios:

  - Web: https://github.com/casadeanalises/lucasfiiresearch-casadeanalises
  - Documentação: https://github.com/casadeanalises/lucasfiiresearch-casadeanalises-docs

# GitBook.io a documentação do projeto

https://lucasfii-research.gitbook.io/docs-lucasfiiresearch/


- ## 📝 Licença

© 2025 Lucas FII Research L&L Consultoria Financeira. Todos os direitos reservados.
