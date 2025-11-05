# Documentação do Dashboard - Resumo

Este diretório contém documentação sobre funcionalidades do Dashboard do Affiliatus.io.

## Documentos Disponíveis

### 📘 Portal do Afiliado (`affiliate-portal.mdx`)

Documentação completa sobre o Portal do Afiliado, incluindo:

#### 1. **Visão Geral**
- O que é o Portal do Afiliado
- Funcionalidades principais
- Benefícios para gestores e afiliados

#### 2. **Ativação e Configuração**
- Como ativar o portal
- Obter URLs públicas (landing page + portal)
- Configurar auto-cadastro de afiliados
- Configurações de segurança

#### 3. **Fluxo de Cadastro**
- Cadastro manual pelo administrador
- Auto-cadastro (se habilitado)
- Processo de aprovação
- Gestão de pendências

#### 4. **Funcionalidades para Afiliados**

**Dashboard Principal:**
- KPIs (Visualizações, Conversões, Comissões)
- Gráficos de performance
- Taxa de conversão e ticket médio
- Tabela de conversões com filtros

**Página de Pagamentos:**
- Saldo disponível destacado
- Estatísticas (Total Recebido, Aguardando, Total Geral)
- Histórico completo de payouts
- Status de cada pagamento

**Navegação:**
- Sidebar dedicada
- Breadcrumbs
- Menu responsivo

#### 5. **Landing Page Pública**
- Hero section customizável
- Cards informativos (comissão, atribuição, cookie, etc.)
- CTAs para cadastro e login
- Design responsivo e moderno

#### 6. **Segurança**
- Sistema de autenticação isolado
- Validações de senha e e-mail
- Controle de acesso por campanha
- Auditoria de ações

#### 7. **Recursos Técnicos**
- URLs e rotas
- APIs utilizadas
- Estrutura de dados
- Fluxo completo (diagrama Mermaid)

#### 8. **Boas Práticas**
- Ativação do portal
- Gestão de auto-cadastro
- Compartilhamento de URLs
- Gestão de afiliados

#### 9. **FAQ**
- Perguntas frequentes sobre o portal
- Respostas sobre segurança, funcionalidades e uso

---

## Estrutura da Documentação

```
dashboard/
├── affiliate-portal.mdx    # Documentação completa do Portal
└── README.md              # Este arquivo
```

---

## Como Usar

Esta documentação está integrada ao site de documentação Affiliatus.io através do arquivo `docs.json`.

Para visualizar:
1. Acesse o site de documentação
2. Navegue até a aba "Guides"
3. Procure pela seção "Dashboard"
4. Clique em "Portal do Afiliado"

---

## Conteúdo Coberto

### ✅ Análise Completa
- [x] Página de configuração do portal (`settings/portal/page.tsx`)
- [x] Landing page pública (`[campaignId]/page.tsx`)
- [x] Página de login (`[campaignId]/login/page.tsx`)
- [x] Página de signup (`[campaignId]/signup/page.tsx`)
- [x] Dashboard do afiliado (`[campaignId]/dashboard/page.tsx`)
- [x] Layout do dashboard (`[campaignId]/dashboard/layout.tsx`)
- [x] Página de pagamentos (`[campaignId]/dashboard/payouts/page.tsx`)

### ✅ Features Documentadas

**Configuração:**
- ID Público da Campanha
- URL do Portal
- Auto-cadastro (ativação/desativação)
- URL da Landing Page

**Landing Page:**
- Hero section com nome e descrição
- Cards informativos (6 cards)
- CTAs para cadastro e login
- Design responsivo

**Autenticação:**
- Login seguro
- Signup com validações
- Aprovação por administrador
- Sessões isoladas

**Dashboard do Afiliado:**
- 4 KPIs principais
- 2 métricas complementares
- 2 gráficos interativos (eventos e receita)
- Seletor de período (7/30/90 dias)
- Tabela de conversões com filtros
- Badges de status coloridos

**Página de Pagamentos:**
- Card de saldo disponível (destacado)
- 3 estatísticas de pagamentos
- Histórico completo com paginação
- Filtros por status
- Detalhes de cada payout

**Navegação:**
- Sidebar com logo e menu
- Breadcrumbs em cada página
- Layout responsivo
- Suporte a dark mode

---

## Melhorias Futuras Sugeridas

1. **Recuperação de Senha**
   - Fluxo self-service para afiliados
   - E-mail com token temporário

2. **Notificações**
   - Alertas de novas conversões
   - Avisos de pagamentos processados
   - Notificações in-app

3. **Exportação de Dados**
   - Download de relatórios em CSV/PDF
   - Exportar histórico de conversões
   - Recibos de pagamento

4. **Materiais de Divulgação**
   - Biblioteca de banners
   - Templates de e-mail
   - Assets compartilháveis

5. **Gamificação**
   - Badges de conquistas
   - Rankings de afiliados
   - Metas e desafios

6. **Multi-idioma**
   - Suporte a inglês e espanhol
   - Seletor de idioma no portal

---

## Suporte

Para dúvidas sobre esta documentação:
- E-mail: suporte@affiliatus.io
- Dashboard: app.affiliatus.io

