# 🥗 NutriBox - Assinatura de Marmitas Saudáveis Personalizadas

> MVP de um serviço de assinatura de refeições saudáveis para rotinas agitadas, desenvolvido com assistência de IA como Co-Founder.

👉 **Status do Projeto:** MVP conceitual validado via prompts. Publicação em nuvem (Lovable Cloud) em fase de implantação.

---

## 🎯 1. A Dor Escolhida
Pessoas que trabalham em regime home office ou presencial intenso não têm tempo para cozinhar refeições saudáveis diariamente e acabam recorrendo a fast-foods caros e pouco nutritivos. A **NutriBox** resolve essa dor oferecendo um plano de assinatura semanal personalizável de marmitas ultracongeladas.

---

## 📊 2. Tamanho de Mercado & Business Model Canvas

### Tamanho de Mercado (Estimativa)
* **TAM (Total Addressable Market):** Mercado de alimentação saudável e marmitas prontas no Brasil (~R$ 35 bilhões/ano).
* **SAM (Serviceable Addressable Market):** Pessoas das classes A e B em grandes centros urbanos que buscam praticidade e nutrição (~R$ 2,5 bilhões/ano).
* **SOM (Serviceable Obtainable Market):** Profissionais de tecnologia e corporativo na cidade local nos primeiros 6 meses (~R$ 150 mil/ano).

### Business Model Canvas (Resumido)
* **Proposta de Valor:** Praticidade, nutrição sob medida e economia de tempo.
* **Segmento de Clientes:** Profissionais ocupados, praticantes de atividades físicas e pessoas em reeducação alimentar.
* **Canais:** Landing Page, Instagram e WhatsApp.
* **Fonte de Receita:** Assinatura mensal/semanal (recorrência).
* **Estrutura de Custos:** Ingredientes, embalagens, taxa de entrega e marketing local.

---

## 🧪 3. Tese do MVP e Processos Manuais

### Tese a Testar
"Profissionais ocupados estão dispostos a assinar um plano semanal de marmitas via formulário simples e fechar a compra diretamente via WhatsApp."

### O que ficou Manual de Propósito
* **Fechamento de Venda:** Atendimento e envio do link de pagamento (Pix/Cartão) feitos manualmente pelo WhatsApp.
* **Gestão de Entregas:** Roteirização e confirmação organizadas manualmente no Painel do Administrador.

---

## 🤖 4. Mega Prompt Utilizado

```markdown
# Contexto e Função
Atue como um Engenheiro de Software Full-Stack e UX Designer especialista em MVPs de e-commerce. Crie uma aplicação Web para a "NutriBox", um serviço de assinatura de marmitas saudáveis.

# Requisitos da Interface
1. Landing Page (Cliente):
   - Hero Section com proposta de valor clara e botão CTA "Montar Meu Plano".
   - Formulário de personalização (objetivo, quantidade de refeições/semana e restrições alimentares).
   - Botão para direcionar os dados do pedido diretamente para o WhatsApp.
2. Painel Administrativo (/admin):
   - Tabela de leads/pedidos recebidos.
   - Status do pedido (Novo Lead, Pagamento Pendente, Confirmado, Entregue).
   - Métricas simples (Total de pedidos, Faturamento estimado).

# Identidade Visual
- Cores: Verde Menta (#10B981) para ação/saúde, Cinza Escuro (#1F2937) para texto e Fundo Branco/Neutro.
- Estilo: Limpo, moderno e responsivo para mobile.
