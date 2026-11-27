

🚀 Code_in_tech — Sistema Integrado de Gestão Empresarial (ERP, PDV & CRM)

O Code_in_tech é uma plataforma web corporativa mobile-first desenvolvida para unificar os três pilares essenciais da operação comercial moderna — ERP (Estoque), PDV (Frente de Caixa) e CRM (Relacionamento e Cobranças) — em um único ecossistema em nuvem, rápido, seguro e intuitivo.

🔗 Acesse o sistema online: Code_in_tech Web App

📋 Índice

Visão Geral e Problema Resolvido

Arquitetura e Módulos Integrados

Controle de Acesso e Segurança (RBAC)

Design System & Identidade Visual

Stack Tecnológica

Como Executar e Configurar

Créditos Institucionais

🎯 Visão Geral e Problema Resolvido

Pequenas e médias empresas frequentemente enfrentam gargalos operacionais causados pelo uso de planilhas isoladas ou softwares desconectados, resultando em divergências de estoque, perda de histórico financeiro de clientes e falhas de segurança no acesso da equipe.

O Code_in_tech resolve esse cenário garantindo integridade transacional em tempo real:

Venda concluída no PDV

Baixa automática imediata no estoque do ERP

Atualização instantânea do histórico do cliente no CRM

Registro imutável nos logs de Auditoria

🧩 Arquitetura e Módulos Integrados

1. 📊 Dashboard Executivo & Financeiro

Monitoramento consolidado de Entradas, Saídas de Dinheiro, Saldo Líquido e Ticket Médio.

Filtros dinâmicos por período (Diário, Semanal, Mensal e Anual) com gráficos comparativos de fluxo de caixa.

2. 🛒 Frente de Caixa (PDV)

Interface otimizada para agilidade no atendimento (desktop, tablet ou smartphone).

Seleção rápida de produtos com validação automática de disponibilidade em estoque.

Vinculação ao perfil do cliente no CRM e suporte a múltiplos métodos de pagamento (Pix, Cartão de Crédito, Dinheiro).

3. 📦 Gestão de Inventário e Catálogo (ERP)

Controle completo de SKUs, categorias, precificação e quantidades disponíveis.

Indicadores visuais inteligentes de Estoque Baixo baseados no estoque mínimo configurado por item.

4. 🤝 Relacionamento e Cobranças (CRM)

Cadastro completo de clientes (Pessoa Física e Jurídica — CPF/CNPJ).

Gestão de saldo devedor, registro detalhado de anotações financeiras, histórico de compras realizadas no PDV e acompanhamento de cobranças pendentes.

🔐 Controle de Acesso e Segurança (RBAC)

O sistema implementa Controle de Acesso Baseado em Funções (Role-Based Access Control) com roteamento blindado: cada perfil visualiza e opera estritamente o escopo autorizado para sua função.

1. Administrador Geral (Dono do Sistema)

Domínio total da plataforma e configurações globais.

Acesso aos logs de auditoria e segurança.

Monitoramento de integridade das tabelas do banco de dados.

2. Gestor / Dono do Negócio (Gestão Estratégica)

Visualização completa dos dashboards financeiros e métricas de vendas.

Cadastro e gerenciamento de produtos no ERP.

Criação, edição e bloqueio de credenciais de operadores.

3. Operador de Caixa (PDV)

Acesso exclusivo à Frente de Caixa e histórico de vendas.

Busca rápida de clientes, seleção de produtos e processamento de pagamentos com baixa automática no ERP.

4. Operador de ERP (Estoque e Catálogo)

Cadastro de novos produtos e peças.

Atualização de preços, categorias e saldos de estoque.

Exclusão de itens obsoletos do catálogo.

5. Operador de CRM (Clientes e Cobranças)

Cadastro, edição e exclusão de perfis de clientes.

Registro de anotações de dívidas, lembretes de cobranças pendentes e histórico de interações.

🎨 Design System & Identidade Visual

Projetado sob princípios modernos de UI/UX com foco em legibilidade, ergonomia visual e responsividade:

Preto Profundo (#09090B): Fundo principal (Dark Mode) de alto contraste e baixo cansaço visual.

Cinza Tecnológico (#27272A / #71717A): Superfícies elevadas, bordas sutis e tipografia secundária.

Azul Corporativo (#2563EB): Ações primárias, indicadores positivos e identidade da marca.

Vermelho Destaque (#DC2626): Alertas críticos, saídas financeiras, estoque baixo e ações destrutivas.

Tema Dual Persistente: Alternância instantânea entre Modo Escuro e Modo Claro, salva automaticamente nas preferências do navegador.

Mobile-First: Layout totalmente adaptável para telas de smartphones, tablets e monitores widescreen.

🛠️ Stack Tecnológica

Frontend: HTML5 Semântico, Tailwind CSS (Design System responsivo) e JavaScript ES6+.

Backend & Banco de Dados: Supabase (PostgreSQL relacional em nuvem + Supabase Auth).

Segurança: Autenticação JWT, isolamento Multi-Tenant e Row Level Security (RLS).

Versionamento & Hospedagem: Git, GitHub e Deploy Contínuo via GitHub Pages.

⚙️ Como Executar e Configurar

1. Clonar o Repositório

git clone https://github.com/Renato-Alho-Dev-Full/code_in_tech_sistema_de_gestao.git
cd code_in_tech_sistema_de_gestao


2. Configurar o Banco de Dados (Supabase)

Crie um projeto gratuito no Supabase.

No SQL Editor, execute o script de criação das tabelas (profiles, products, clients, sales, expenses, audit_logs).

Em Authentication > Providers > Email, desative a opção Confirm email para permitir a criação imediata de operadores pelo painel do Gestor/Admin.

Copie a Project URL e a Publishable / Anon Key em Project Settings > API Keys.

3. Conectar no Aplicativo

Abra o arquivo index.html no navegador ou acesse o link publicado no GitHub Pages.

Na tela inicial de login, clique no botão "Configurar Banco", insira a Project URL e a Anon Key do seu Supabase e salve.

Faça login com as credenciais cadastradas no Supabase Auth.

🎓 Créditos Institucionais

Projeto desenvolvido como produto tecnológico no âmbito do Curso Técnico em Informática:

Instituição: EETEPA Dr. Celso Malcher

Desenvolvedor / Autor: Renato Alho

Orientação: Profª. Me. Cintia Rodrigues

© 2026 Code_in_tech — Soluções em T.I. Todos os direitos reservados.

































































































































































