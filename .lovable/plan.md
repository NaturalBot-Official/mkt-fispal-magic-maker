
## Recriar Landing Page — Fispal 2026

Recriar a landing page de captação de leads inspirada na original da Natural Bot, atualizando o evento para **Fispal Food Service 2026** com a nova data **26 a 29 de maio**.

### Estrutura da página (single page, scroll vertical)

**1. Header**
- Logo Natural Bot centralizado no topo (sobre fundo claro)

**2. Hero / Seção principal (duas colunas em desktop, empilhada no mobile)**

Coluna esquerda — informações do evento:
- Logo / badge "Fispal Food Service 2026"
- Título: **"Garanta seu INGRESSO GRATUITO para a Fispal Food Service 2026!"**
- Subtítulo: "O maior evento do setor, reunindo as principais tendências, inovações e oportunidades de negócios para restaurantes, lanchonetes, pizzarias, cafeterias e muito mais."
- 📅 Data: **26 a 29 de maio**
- 📍 Local: Distrito Anhembi – São Paulo
- Texto sobre a Natural Bot ser expositora oficial e oferecer **CÓDIGO VIP** exclusivo
- Lista "O que você vai encontrar na Fispal:" com 3 bullets (✔️ Novidades e inovações / Networking / Soluções para vendas)
- "_Convites limitados!_"

Coluna direita — formulário (card rosa magenta, igual ao original):
- Título: "Preencha o formulário para receber o CÓDIGO VIP"
- Campos: Nome*, Email*, Celular* (com bandeira BR), Trabalha com delivery? (Sim/Não radio), Empresa*, Segmento de atuação* (select com opções: Açaí/Sorvetes, Culinária oriental, Esfiharia/Árabe, Hamburgueria, Lanches/Saladas, Marmitas/Prato feito, Padaria/Confeitaria, Pizzaria, Outro)
- Botão amarelo **"RECEBER CÓDIGO VIP"**
- Validação dos campos obrigatórios + toast de sucesso ao enviar (sem backend — apenas feedback visual)

**3. Faixa rosa divisória**

**4. Seção "Sobre a Natural Bot"**
- Título: "Sobre a Natural Bot"
- Tagline: "Somos o 1° Copiloto de Vendas com IA para restaurantes do Brasil!"
- Grid com 4 features (ícone + título + descrição):
  - **Inteligência Artificial** — automação de atendimento, cobrança e ordens de serviço
  - **Integração com Monitores** — pedidos seguem para o KDS após pagamento
  - **Atendimento Multilíngue** — mais de 60 línguas
  - **Linguagem Personalizada** — propósito, arquétipo e tom de voz da marca
- Botão **"SAIBA MAIS"** linkando para naturalbot.com.br

### Design

- **Paleta**: rosa magenta vibrante (cor de destaque do card de formulário e faixa), amarelo no CTA, fundo claro/off-white, textos em cinza escuro — fiel à identidade visual atual da Natural Bot
- **Background hero**: imagem suave de pratos/comida com overlay claro (estilo da original)
- **Tipografia**: sans-serif moderna, títulos em peso bold
- **Responsivo**: layout em duas colunas no desktop, empilhado no mobile com formulário no final
- **Tokens semânticos** definidos em `index.css` + `tailwind.config.ts` (sem cores hardcoded nos componentes)

### Observações

- A página será apenas frontend; o formulário exibe um toast de confirmação ao enviar (não envia para nenhum CRM). Se quiser integrar com RD Station, HubSpot ou enviar por e-mail/WhatsApp depois, adicionamos numa próxima etapa.
