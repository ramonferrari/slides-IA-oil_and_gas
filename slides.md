---
theme: seriph
colorSchema: both
themeConfig:
  appearance: dark
  shortTitle: "Tendências de IA em O&G: Houston 2026"
background: false
transition: slide-left
fonts:
  sans: Space Grotesk
  serif: Space Grotesk
  mono: JetBrains Mono
  provider: none
class: text-left
---

<!-- Slide 01 — Capa -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center px-16">
<div class="glass px-16 py-10 w-full max-w-4xl mx-auto">
  <div class="text-xs font-mono tracking-widest mb-4" style="color: var(--rf-primary)">HOUSTON, TX | ABRIL/2026</div>
  <h1 class="text-5xl font-bold leading-tight mb-4" style="color: var(--rf-primary); font-size: 3.2rem">Tendências de IA em O&G<br>O que já temos aqui</h1>
  <p class="text-xl mb-4" style="color: var(--rf-muted)">Disseminação do 11th Annual AI in Oil & Gas Conference</p>
  <div class="text-base" style="color: var(--rf-secondary)">Ramon Moreno Ferrari | CSDA / UO-ES</div>
</div>
<div class="absolute bottom-6 right-20">
  <span class="font-mono text-xs tracking-widest font-bold" style="color: var(--rf-primary)">PETROBRAS</span>
</div>
</div>

<!--
"Bom dia, pessoal. Em abril tive a oportunidade de participar do maior evento global de IA aplicada ao setor de óleo e gás, em Houston. Hoje vou compartilhar o que vi, o que aprendi — e como isso se conecta com o que já estamos construindo aqui no Espírito Santo. Temos 50 minutos, então vamos com calma."
-->

---

<!-- Slide 02 — O Evento: Números -->

# O Evento

<div class="grid grid-cols-3 gap-2 mt-1">
  <div class="glass text-center" style="padding: 0.8rem 0.4rem;">
    <div style="font-size: 1.6rem; font-weight: 700; color: var(--rf-primary)">423</div>
    <div style="font-size: 0.7rem; margin-top: 0.2rem; color: var(--rf-text)">participantes</div>
  </div>
  <div class="glass text-center" style="padding: 0.8rem 0.4rem;">
    <div style="font-size: 1.6rem; font-weight: 700; color: var(--rf-primary)">63</div>
    <div style="font-size: 0.7rem; margin-top: 0.2rem; color: var(--rf-text)">palestrantes</div>
  </div>
  <div class="glass text-center" style="padding: 0.8rem 0.4rem;">
    <div style="font-size: 1.6rem; font-weight: 700; color: var(--rf-primary)">91</div>
    <div style="font-size: 0.7rem; margin-top: 0.2rem; color: var(--rf-text)">patrocinadores</div>
  </div>
</div>

<Spacer :h="10"/>


<div class="img-container glass">
  <img src="./slide2.png" style="height: 250px; object-fit: contain;" />
</div>

<style>
.slidev-page-2 .glass { padding: 0.8rem !important; }
.slidev-page-2 .img-container { margin-top: 2px; display: flex; justify-content: center; width: 100%; }
.slidev-page-2 .img-container img { height: 250px; object-fit: contain; }
</style>

<!--
"O evento reuniu 423 participantes — o maior número da história do evento. Estavam presentes ExxonMobil, Chevron, BP, Oxy, Saudi Aramco, Shell, Murphy Oil… e a Petrobras. Líderes de dados, CDOs, engenheiros, cientistas de dados e gestores de operações — todos no mesmo espaço discutindo como a IA está transformando o setor."
-->

---

<!-- Slide 03 — O Evento: Clima -->

# O Evento

<div class="glass" style="height: 380px; display: flex; align-items: center; justify-content: center; margin-top: 2px; overflow: hidden;">
  <img src="./slide3.png" style="width: 100%; height: 100%; object-fit: contain;" />
</div>

<!--
"O clima do evento foi de urgência construtiva. Não era mais uma conferência sobre o futuro da IA — era sobre execução. As palestras eram práticas, com casos reais, números de ROI, lições aprendidas. Eu saí de lá com a sensação de que o mundo está se movendo rápido — e com a certeza de que estamos no caminho certo aqui no ES."
-->

---

<!-- Slide 04 — Os 11 Grandes Temas -->

# Os 11 Grandes Temas do Evento

<div class="grid grid-cols-2 gap-4 mt-3">

<GlassCard title="Eixo Técnico" subtitle="🔵 TECNOLOGIA">

- Agentes Autônomos (Agentic AI)
- Digital Twins e Manutenção Preditiva
- Inspeção por Drones e Visão Computacional
- IA Generativa e RAG Corporativo
- Modelos Híbridos e Escolha da Ferramenta Certa
- Qualidade e Orquestração de Dados

</GlassCard>

<GlassCard title="Eixo Humano" subtitle="🟠 ORGANIZAÇÃO">

- Superando a fase de "Purgatório dos Pilotos"
- Governança, Segurança e Responsabilidade
- Mudança Organizacional e Liderança
- Velocidade da Inovação e Gestão de Riscos
- Casos de Uso com Ganhos Tangíveis

</GlassCard>

</div>

<style>
.slidev-page-4 .glass { padding: 0.8rem 1.2rem !important; }
.slidev-page-4 .rf-card-title { font-size: 1.1rem !important; margin-bottom: 0.4rem !important; }
.slidev-page-4 .rf-card-subtitle { margin-bottom: 0.4rem !important; }
.slidev-page-4 li { margin: 0.1rem 0 !important; margin-left: 1.5rem !important; }
.slidev-page-4 p, .slidev-page-4 li { font-size: 1.2rem !important; line-height: 1.5 !important; }
</style>

<!--
"Os temas se organizaram em dois grandes eixos. De um lado, as tecnologias emergentes. Do outro, os desafios organizacionais — que, na minha visão, foram o coração do evento. Hoje vou mergulhar nos dois. Vamos começar pelo que me chamou mais atenção: os desafios que o mundo enfrenta para fazer a IA funcionar de verdade."
-->

---
transition: fade
---

<!-- Slide 05 — Seção: Desafios -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center px-16">
  <div class="glass px-16 py-12 w-full max-w-3xl mx-auto">
    <div class="text-xs font-mono tracking-widest mb-4" style="color: var(--rf-primary)">DESAFIOS E DIFICULDADES</div>
    <h1 class="text-5xl font-bold leading-tight mb-4">Por que a IA ainda<br>trava nas organizações?</h1>
    <Subtitle>As barreiras reais que o setor enfrenta, para além do hype</Subtitle>
  </div>
</div>

<!--
"Antes de falar das soluções, preciso falar dos problemas. Uma coisa que me marcou foi a honestidade dos palestrantes sobre as dificuldades reais. Não foi uma conferência de hype — foi uma conferência de gente que já errou e aprendeu. Vamos ver os principais desafios que o setor enfrenta."
-->

---

<!-- Slide 06 — O Purgatório dos Pilotos (Parte 1) -->

# O Purgatório dos Pilotos

<div class="glass mt-1" style="text-align: center;">
  <p style="font-size: 0.88rem; font-style: italic; color: var(--rf-text); line-height: 1.3;">
    "Defina o entregável concreto antes de construir qualquer modelo." -- Lesley Ward, Novanix AI
  </p>
  <p style="font-size: 0.68rem; margin-top: 0.2rem; font-family: 'JetBrains Mono', monospace; color: var(--rf-muted)">— Lesley Ward, Novanix AI</p>
</div>

```mermaid
flowchart LR
  P1([Piloto]) --> D{Integrado?}
  D -- "❌ Não" --> P2([Piloto]) --> P3([Piloto]) --> E([Esquecimento])
  D -- "✅ Sim" --> W([Workflow real]) --> H([Hábito operacional])
  style E fill:#ef4444,color:#fff,stroke:none
  style H fill:#35996e,color:#fff,stroke:none
  style W fill:#1a5c42,color:#fff,stroke:#35996e
```

<style>
.slidev-page-6 .rf-architecture { padding: 0 !important; margin: 0 !important; }
.slidev-page-6 .glass { padding: 0.4rem 0.8rem !important; }
.slidev-page-6 p, .slidev-page-6 li { font-size: 0.82rem !important; line-height: 1.3 !important; }
</style>

<!--
"O tema mais recorrente foi o 'pilot purgatory'. As empresas conseguem fazer um piloto de IA funcionar, mas não conseguem transformá-lo em operação real."
-->

---

<!-- Slide 06b — O Purgatório dos Pilotos (Parte 2) -->

# O Purgatório dos Pilotos: As 3 Causas

<div class="grid grid-cols-3 gap-3 mt-2">
  <GlassCard title="Sem dono na operação em rotina" subtitle="CAUSA 1">Sem responsável por prover abrangência ao piloto</GlassCard>
  <GlassCard title="Solução fora dos workflows" subtitle="CAUSA 2">Solução não foi mapeada nos processos existentes</GlassCard>
  <GlassCard title="Sucesso técnico ≠ adoção" subtitle="CAUSA 3">Modelo funciona, mas ninguém usa no dia a dia</GlassCard>
</div>

<div class="glass mt-3" style="text-align: center;">
  <p style="font-size: 0.9rem">
    Piloto que tecnicamente funciona mas nunca entra no workflow real 
    <span style="color: #60c69a; font-weight: 700"><strong>não gera valor</strong></span>.  
  </p>
</div>

<style>
.slidev-page-7 .glass { padding: 0.5rem 0.9rem !important; }
.slidev-page-7 .rf-card-title { font-size: 0.95rem !important; margin-bottom: 0.2rem !important; }
.slidev-page-7 .rf-card-subtitle { margin-bottom: 0.2rem !important; font-size: 0.75rem !important; }
.slidev-page-7 p, .slidev-page-7 li { font-size: 0.85rem !important; line-height: 1.35 !important; }
</style>

<!--
"Três causas raízes para o pilot purgatory que vimos em Houston."
-->

---

<!-- Slide 09 — Dados: o Gargalo -->

# Dados: o alicerce e o maior gargalo

<div class="glass mt-2" style="text-align: center;">
  <p style="font-size: 1.05rem; line-height: 1.5; font-style: italic; color: var(--rf-text)">
    "A IA amplifica tanto boas decisões quanto erros."
  </p>
  <p style="font-size: 0.7rem; margin-top: 0.2rem; font-family: 'JetBrains Mono', monospace; letter-spacing: 0.12em; color: var(--rf-muted)">— Syniti, AI in Oil & Gas 2026</p>
</div>

<div class="grid grid-cols-3 gap-3 mt-3">
  <GlassCard title="Dados incompletos" subtitle="PROBLEMA 1">Incompletos, inconsistentes ou sem contexto operacional</GlassCard>
  <GlassCard title="Sistemas desconectados" subtitle="PROBLEMA 2">IT, OT e ET que nunca foram pensados para conversar</GlassCard>
  <GlassCard title="Sem governança" subtitle="PROBLEMA 3">Falta de taxonomia, metadados e gestão de qualidade</GlassCard>
</div>

<style>
.slidev-page-8 .glass { padding: 0.5rem 1rem !important; }
.slidev-page-8 .rf-card-title { font-size: 0.95rem !important; margin-bottom: 0.2rem !important; }
.slidev-page-8 .rf-card-subtitle { margin-bottom: 0.2rem !important; font-size: 0.75rem !important; }
.slidev-page-8 p, .slidev-page-8 li { font-size: 0.85rem !important; line-height: 1.35 !important; }
</style>

<!--
"A Syniti teve uma fala que ficou na minha cabeça: 'A IA amplifica tanto boas decisões quanto erros.' Dados ruins escalam tão eficientemente quanto dados bons. E o problema de dados no setor de O&G é estrutural: temos sistemas de IT, OT e ET que nunca foram pensados para conversar. Tags diferentes para o mesmo ativo, hierarquias inconsistentes, metadados ausentes. Sem resolver isso, qualquer modelo de IA vai ser construído sobre areia."
-->

---

<!-- Slide 08 — Segurança e Governança (Parte 1) -->

# Segurança, Governança e Movimento Rápido

<div class="grid grid-cols-2 gap-3 mt-2">

<GlassCard title="Riscos reais" subtitle="❌ PREOCUPAÇÕES">

- Lock-in em fornecedor único
- Agentes sem limites claros
- IA em sistemas críticos sem auditoria
- Código gerado sem revisão humana

</GlassCard>

<GlassCard title="O que funciona" subtitle="✅ BOAS PRÁTICAS">

- Human-in-the-loop em decisões críticas
- Responsible AI proporcional ao risco
- Rastreabilidade e trilha de auditoria
- Governança como requisito primeiro

</GlassCard>

</div>

<div class="glass mt-2" style="text-align: center;">
  <p style="font-size: 0.9rem; font-style: italic">
    Velocidade e governança não são opostos.<br>
    <span style="color: #35996e; font-weight: 700">São complementares.</span>
  </p>
</div>

<style>
.slidev-page-9 .glass { padding: 0.5rem 0.9rem !important; }
.slidev-page-9 .rf-card-title { font-size: 0.95rem !important; margin-bottom: 0.2rem !important; }
.slidev-page-9 .rf-card-subtitle { margin-bottom: 0.2rem !important; font-size: 0.75rem !important; }
.slidev-page-9 p, .slidev-page-9 li { font-size: 0.85rem !important; line-height: 1.35 !important; }
</style>

<!--
"A Chevron Phillips teve uma palestra provocativa chamada 'Hype vs. Reality'. Brent Railey foi direto: o custo da inação é alto — mas a pressa sem governança pode ser pior."
-->

---

<!-- Slide 08b — Segurança e Governança (Parte 2) -->

# Segurança e Governança: Na Prática

<div class="grid grid-cols-2 gap-2 mt-1">
  <ImagePanel src="./slide8-1.png" position="center" width="100%" fit="contain" />
  <ImagePanel src="./slide8-2.png" position="center" width="100%" fit="contain" />
</div>

<div class="glass mt-2" style="text-align: center;">
  <p style="font-size: 0.85rem">
    Avaliação ao risco, rastreabilidade e educação contínua.
  </p>
</div>

<style>
.slidev-page-10 .glass { padding: 0.5rem 1rem !important; }
.slidev-page-10 p { font-size: 0.85rem !important; line-height: 1.3 !important; }
</style>

<!--
"A Chevron apresentou seu framework de Responsible AI — avaliação proporcional ao risco, rastreabilidade, educação da força de trabalho. A mensagem: velocidade e governança não são opostos. São complementares."
-->

---

<!-- Slide 11 — O Maior Desafio é Humano -->

# O Maior Desafio é Humano

<div style="display: grid; grid-template-columns: 1fr 2.3fr; gap: 2rem; margin-top: 1.5rem;">

<div class="glass" style="text-align: center; display: flex; flex-direction: column; justify-content: center; padding: 1.2rem;">
  <p style="font-size: 0.95rem; font-weight: 700; line-height: 1.3;">
    <span style="color: #EC635E; font-size: 1.6rem; display: block; margin-bottom: 0.4rem;">71%+</span>
    das falhas são<br>
    questões organizacionais, culturais e de liderança
  </p>
</div>

<div class="flex flex-col gap-2">
  <div class="glass" style="padding: 0.9rem 1rem; border-left: 4px solid #EC635E; display: flex; align-items: center; gap: 0.8rem;">
    <div style="font-size: 1.6rem; flex-shrink: 0;">💰</div>
    <div>
      <div style="font-size: 0.88rem; font-weight: 700; margin-bottom: 0.2rem;">Incentivos inadequados</div>
      <p style="font-size: 0.76rem; margin: 0; color: var(--rf-text);">Não há alinhamento entre objetivos e recompensas</p>
    </div>
  </div>

  <div class="glass" style="padding: 0.9rem 1rem; border-left: 4px solid #9678E8; display: flex; align-items: center; gap: 0.8rem;">
    <div style="font-size: 1.6rem; flex-shrink: 0;">🧭</div>
    <div>
      <div style="font-size: 0.88rem; font-weight: 700; margin-bottom: 0.2rem;">Liderança reverte à intuição</div>
      <p style="font-size: 0.76rem; margin: 0; color: var(--rf-text);">Decisões data-driven são abandonadas sob pressão</p>
    </div>
  </div>

  <div class="glass" style="padding: 0.9rem 1rem; border-left: 4px solid #7DD5DB; display: flex; align-items: center; gap: 0.8rem;">
    <div style="font-size: 1.6rem; flex-shrink: 0;">👥</div>
    <div>
      <div style="font-size: 0.88rem; font-weight: 700; margin-bottom: 0.2rem;">Papéis não redesenhados</div>
      <p style="font-size: 0.76rem; margin: 0; color: var(--rf-text);">Equipes recebem ferramentas mas responsabilidades não mudam</p>
    </div>
  </div>

  <div class="glass" style="padding: 0.9rem 1rem; border-left: 4px solid #ABDB2A; display: flex; align-items: center; gap: 0.8rem;">
    <div style="font-size: 1.6rem; flex-shrink: 0;">❓</div>
    <div>
      <div style="font-size: 0.88rem; font-weight: 700; margin-bottom: 0.2rem;">Responsabilidade indefinida</div>
      <p style="font-size: 0.76rem; margin: 0; color: var(--rf-text);">Ninguém é dono dos resultados da IA na operação</p>
    </div>
  </div>
</div>

</div>

<style>
.slidev-page-11 .glass { padding: 1.2rem 1.4rem !important; }
.slidev-page-11 p { font-size: 0.85rem !important; line-height: 1.4 !important; margin: 0 !important; }
</style>

<!--
"Uma das palestras mais marcantes foi da Lisa Williams, da Dow. Ela disse: 71% das falhas em transformações de IA são organizacionais. Não é o modelo que falha — é a organização que não muda junto. Líderes que endossam a IA verbalmente, mas revertem à intuição quando a recomendação contraria a experiência deles. Times que recebem mais ferramentas sem ter os papéis redesenhados. Isso ressoa muito com a nossa realidade."
-->

---
transition: fade
---

<!-- Slide 12 — Transição: Tendências Tecnológicas -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center px-16">
  <div class="glass px-16 py-12 w-full max-w-3xl mx-auto">
    <div class="text-xs font-mono tracking-widest mb-4" style="color: var(--rf-primary)">TENDÊNCIAS TECNOLÓGICAS</div>
    <h1 class="text-5xl font-bold leading-tight mb-4">Agora, o que está funcionando</h1>
    <Subtitle>As 5 tendências tecnológicas que mais  chamaram atenção</Subtitle>
    <Spacer :h="24" />
    <div class="flex justify-center gap-10 text-4xl">
      <div class="flex flex-col items-center gap-1"><span>🤖</span><span class="text-xs font-mono" style="color: var(--rf-muted)">Agentes</span></div>
      <div class="flex flex-col items-center gap-1"><span>🏭</span><span class="text-xs font-mono" style="color: var(--rf-muted)">Digital Twins</span></div>
      <div class="flex flex-col items-center gap-1"><span>🚁</span><span class="text-xs font-mono" style="color: var(--rf-muted)">Drones</span></div>
      <div class="flex flex-col items-center gap-1"><span>📄</span><span class="text-xs font-mono" style="color: var(--rf-muted)">IA Generativa</span></div>
      <div class="flex flex-col items-center gap-1"><span>📊</span><span class="text-xs font-mono" style="color: var(--rf-muted)">Responsible AI</span></div>
    </div>
  </div>
</div>

<!--
"Depois de entender os desafios, vamos ao que está funcionando. Vou apresentar as cinco tendências tecnológicas que mais me impressionaram — com exemplos reais de empresas que já estão colhendo resultado."
-->

---

<!-- Slide 13 — Tendência 1: Agentes Autônomos (Diagrama) -->

# Tendência 1: Agentes Autônomos

<div style="display: flex; align-items: center; justify-content: center; height: 100%; margin-top: -2rem;">
<ArchitectureFlow>

```mermaid
flowchart LR
  A([🤖 Chatbot]) --> B([🧭 Copiloto]) --> C([⚙️ Agente]) --> D([🕸️ Multiagente])
  style A fill:#1e3a5f,color:#ccc,stroke:#35996e
  style B fill:#1e4a6f,color:#ccc,stroke:#35996e
  style C fill:#1e5a7f,color:#fff,stroke:#35996e
  style D fill:#35996e,color:#fff,stroke:#35996e
```

</ArchitectureFlow>
</div>

<style>
.slidev-page-13 .rf-architecture { padding: 1rem 2rem !important; margin: 0 auto !important; }
</style>

<!--
"Uma tendência muito marcante foi a agentic AI — sistemas de múltiplos agentes autônomos que colaboram para resolver problemas complexos."
-->

---

<!-- Slide 13b — Agentes Autônomos (Case Real) -->

# Tendência 1: Agentes Autônomos — Case Real

<div style="display: flex; align-items: center; justify-content: center; height: 100%; margin-top: -2rem;">
  <img src="./slide11.png" style="max-width: 90%; max-height: 80%; object-fit: contain;" />
</div>

<!--
"A NTT DATA mostrou um caso real: seis agentes especializados trabalhando em conjunto para detectar, diagnosticar e prevenir falhas em fundo de poço. Cada agente tem um papel específico. O humano entra apenas para aprovar a decisão final. O sistema estima NPT evitado em tempo real. Isso é operação agentica — e está chegando."
-->

---

<!-- Slide 14 — Tendência 2: Digital Twins (Cases) -->

# Tendência 2: Digital Twins e Manutenção Preditiva

<div style="margin-top: 3rem;">

<GlassCard title="Cases Reais — Covestro" subtitle="DETECÇÃO PRECOCE">

**Válvula lenta:** atuador 3× mais devagar → troca proativa

**Compressor:** anomalia detectada **5 meses antes** do evento

**Bomba:** desvio de curva → troca preventiva para reserva

</GlassCard>

<div style="margin-top: 1rem;">
<Callout type="info">
Digital twin sem workflow de resposta não gera valor. Tecnologia + processo faz diferença.
</Callout>
</div>

</div>

<!--
"A Covestro tem 502 válvulas de segurança e 266 válvulas de controle monitoradas em tempo real."
-->

---

<!-- Slide 14b — Digital Twins: Covestro -->

# Tendência 2: Digital Twins — Dashboard Covestro

<div style="display: flex; align-items: center; justify-content: center; height: 100%; margin-top: -2rem;">
  <img src="./slide12.png" style="max-width: 90%; max-height: 85%; object-fit: contain;" />
</div>

<style>
.slidev-page-14 .glass { padding: 0.65rem 1rem !important; }
.slidev-page-14 .rf-card-title { font-size: 1rem !important; margin-bottom: 0.3rem !important; }
.slidev-page-14 .rf-card-subtitle { margin-bottom: 0.3rem !important; }
.slidev-page-14 p, .slidev-page-14 li { font-size: 0.88rem !important; line-height: 1.45 !important; }
</style>

<!--
"A Covestro tem 502 válvulas de segurança e 266 válvulas de controle monitoradas em tempo real. Em um dos casos apresentados, o sistema detectou que uma válvula demorava 3 vezes mais para abrir — a equipe agiu antes da falha. Em outro, uma anomalia em compressor foi detectada 5 meses antes do evento real. A lição: digital twin sem workflow de resposta definido não gera valor. Tecnologia mais processo é o que faz diferença."
-->

---

<!-- Slide 15 — Tendência 3: Drones e Visão Computacional -->

# Tendência 3: Inspeção por Drones e Visão Comput.

<div class="grid grid-cols-2 gap-4 mt-3">

<div style="max-height: 340px; overflow: hidden;">
  <ImagePanel src="./slide13.png" position="center" width="100%" fit="contain" caption="Levatas/Skydio — Dashboard de Inspeções Autônomas" />
</div>

<div>
<div class="rf-metrics-3 mb-3" style="gap: 1.2rem; display: flex; transform: scale(0.5); transform-origin: top left; margin-bottom: -4rem;">
  <MetricCard value="45" label="missões" />
  <MetricCard value="650" label="inspeções IA" />
  <MetricCard value="36" label="anomalias" />
</div>

<GlassCard title="" subtitle="VISÃO COMPUTACIONAL: Capacidades">

- Anomalia térmica e infravermelha
- Detecção de trincas e corrosão
- Leitura automática de manômetros
- Detecção de fumaça, fogo e intrusões

</GlassCard>
</div>

</div>

<style>
.slidev-page-15 .glass { padding: 0.6rem 1rem !important; }
.slidev-page-15 .rf-value { font-size: 0.65rem !important; font-weight: 700 !important; }
.slidev-page-15 .rf-label { margin-top: 0.02rem !important; font-size: 0.45rem !important; }
.slidev-page-15 .rf-card-title { font-size: 1rem !important; margin-bottom: 0.3rem !important; }
.slidev-page-15 .rf-metrics-3 { gap: 1.2rem !important; margin-bottom: 0.8rem !important; }
.slidev-page-15 .rf-metrics-3 > div { padding: 0.3rem 0.5rem !important; }
.slidev-page-15 .rf-card-subtitle { margin-bottom: 0.3rem !important; }
.slidev-page-15 p, .slidev-page-15 li { font-size: 0.88rem !important; line-height: 1.45 !important; }
</style>

<!--
"A Levatas, com drones Skydio, apresentou inspeções totalmente autônomas. O drone voa a rota programada, captura dados térmicos e visuais, e a IA analisa cada ativo e emite alertas em tempo real. Os clientes incluem Chevron e ExxonMobil. Para ativos offshore com acesso difícil e riscos de trabalho em altura, esse tipo de solução tem potencial enorme. O ROI está na redução de riscos humanos e na detecção precoce de anomalias."
-->

---
transition: fade
---

<!-- Slide 16 — Transição: IA Generativa -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center px-16">
  <div class="glass px-16 py-12 w-full max-w-3xl mx-auto">
    <div class="text-xs font-mono tracking-widest mb-4" style="color: var(--rf-primary)">TENDÊNCIA 4</div>
    <h1 class="text-5xl font-bold leading-tight mb-4">IA Generativa:<br>da conversa para a operação</h1>
    <Subtitle>Como o setor está usando LLMs além do chatbot</Subtitle>
  </div>
</div>

<!--
"Agora quero dedicar um tempo especial à IA generativa — porque foi um tema que tem evoluído dramaticamente nos últimos anos e que tem muito a ver com o que estamos fazendo aqui na ES. O setor já passou da fase 'vamos testar um chatbot' para casos de uso reais, integrados a sistemas de produção."
-->

---

<!-- Slide 17 — IA Generativa: Cases Reais -->

# IA Generativa: Casos de Uso Reais

<div class="grid grid-cols-3 gap-4 mt-3">

<div class="glass" style="border-top: 3px solid #35996e">
  <div class="text-xs font-mono tracking-widest mb-1" style="color: var(--rf-primary)">OUTSYSTEMS + PETROBRAS</div>
  <div style="font-size: 0.95rem; font-weight: 700; margin-bottom: 0.4rem">Produtividade</div>
  <p>Análises que levavam <strong>dias</strong> agora levam <strong>minutos</strong>.</p>
  <p style="font-size: 0.75rem; margin-top: 0.5rem; font-family: 'JetBrains Mono', monospace; color: var(--rf-primary)">Petrobras citada como caso de sucesso</p>
</div>

<div class="glass" style="border-top: 3px solid #9678E8">
  <div class="text-xs font-mono tracking-widest mb-1" style="color: #9678E8">OXY — ACELERAÇÃO DE DEV</div>
  <div style="font-size: 0.95rem; font-weight: 700; margin-bottom: 0.4rem">Desenvolvimento de Software</div>
  <div style="text-align: center; margin: 0.3rem 0">
    <div style="font-size: 3rem; font-weight: 700; color: var(--rf-primary); line-height: 1">41%</div>
    <div style="font-size: 0.8rem; opacity: 0.7; margin-top: 0.2rem">do código gerado por IA</div>
  </div>
  <p style="font-size: 0.8rem">Com revisão humana obrigatória</p>
</div>

<div class="glass" style="border-top: 3px solid #7DD5DB">
  <div class="text-xs font-mono tracking-widest mb-1" style="color: #7DD5DB">PERPLEXITY ENTERPRISE</div>
  <div style="font-size: 0.95rem; font-weight: 700; margin-bottom: 0.4rem">Crescimento do Setor</div>
  <div style="text-align: center; margin: 0.3rem 0">
    <div style="font-size: 3rem; font-weight: 700; color: var(--rf-primary); line-height: 1">235%</div>
    <div style="font-size: 0.8rem; opacity: 0.7; margin-top: 0.2rem">crescimento previsto</div>
  </div>
  <p style="font-size: 0.8rem">De $4bi (2026) para $13,4bi (2029)</p>
</div>

</div>

<style>
.slidev-page-17 .glass { padding: 0.65rem 1rem !important; }
.slidev-page-17 p, .slidev-page-17 li { font-size: 0.85rem !important; line-height: 1.4 !important; }
</style>

<!--
"Três cases marcantes de vendedoras. A Outsystems mencionou a Petrobras como exemplo de aumento de produtividade. A Oxy foi traz números: usa IA para acelerar o próprio desenvolvimento de software — 41% do código já é gerado por IA, com revisão humana obrigatória. E a Perplexity mostrou como um assistente corporativo pode substituir horas de pesquisa manual."
-->

---

<!-- Slide 17b — IA Generativa: Cases Reais (Imagem) -->

# IA Generativa: Crescimento do Mercado

<div style="display: flex; align-items: center; justify-content: center; height: 100%; margin-top: -2rem;">
  <img src="./slide15.png" style="max-width: 70%; max-height: 70%; object-fit: contain;" />
</div>

---

<!-- Slide 18 — RAG Corporativo -->

# IA Generativa: RAG e Dados Corporativos

```mermaid
flowchart LR
  Q([❓ Pergunta]) --> R[Busca nas fontes internas]
  R --> C[Contexto + LLM]
  C --> A([✅ Resposta rastreável])
  style Q fill:#1e3a5f,color:#fff,stroke:#35996e
  style A fill:#35996e,color:#fff,stroke:#35996e
```

<div class="grid grid-cols-3 gap-3 mt-0">
  <GlassCard title="" subtitle="🔐 PILAR 1: Segurança">Controle de acesso granular — dados no perímetro corporativo</GlassCard>
  <GlassCard title="" subtitle="📊 PILAR 2: DQ">Metadados e conectores definem se o RAG responde certo</GlassCard>
  <GlassCard title="" subtitle="✅ PILAR 3: Auditoria">Rastreabilidade das fontes e trilha de compliance</GlassCard>
</div>

---

# IA Generativa: RAG e Dados Corporativos

<Spacer :h="10"/>

<div style="margin-top: 20px;">
<Callout type="warning">
  <div style="font-size: 1.4rem; line-height: 1.6;">
    "Sem bons conectores e dados governados, o RAG responde errado com muita confiança." — Universidade de Houston
  </div>
</Callout>
</div>

<style>
.slidev-page-16 .rf-architecture { padding: 0.65rem 1.25rem !important; }
.slidev-page-16 .glass { padding: 0.6rem 1rem !important; }
.slidev-page-16 .rf-card-title { font-size: 1rem !important; margin-bottom: 0.3rem !important; }
.slidev-page-16 .rf-card-subtitle { margin-bottom: 0.3rem !important; }
.slidev-page-16 p, .slidev-page-16 li { font-size: 0.88rem !important; line-height: 1.4 !important; }
</style>

<!--
"O modelo técnico mais discutido para IA generativa corporativa foi o RAG — Retrieval-Augmented Generation. Em vez de o modelo inventar respostas, ele busca nas suas fontes internas: manuais, relatórios, dados operacionais. Mas um representante da Universidade de Houston foi direto: sem bons conectores e dados bem governados, o RAG responde errado com muita confiança. A qualidade dos dados não é detalhe técnico — é o que determina se o sistema vai gerar valor or gerar ruído."
-->

---

<!-- Slide 19 — Níveis de Maturidade de IA Generativa -->

# IA Generativa: Níveis de Maturidade

<div class="grid grid-cols-2 gap-4 mt-2">
  <div class="glass" style="padding: 1.4rem 1rem; min-height: 100px; display: flex; flex-direction: column; justify-content: center;">
    <div style="font-size: 1.1rem; font-weight: 700; color: var(--rf-primary); margin-bottom: 0.6rem;">Nível 1</div>
    <div style="font-size: 0.95rem; line-height: 1.5;">Assistente: Responde perguntas e gera textos sob demanda</div>
  </div>
  <div class="glass" style="padding: 1.4rem 1rem; min-height: 100px; display: flex; flex-direction: column; justify-content: center;">
    <div style="font-size: 1.1rem; font-weight: 700; color: #9678E8; margin-bottom: 0.6rem;">Nível 2</div>
    <div style="font-size: 0.95rem; line-height: 1.5;">Copiloto: Sugere ações, preenche formulários e resume</div>
  </div>
  <div class="glass" style="padding: 1.4rem 1rem; min-height: 100px; display: flex; flex-direction: column; justify-content: center;">
    <div style="font-size: 1.1rem; font-weight: 700; color: #9678E8; margin-bottom: 0.6rem;">Nível 3</div>
    <div style="font-size: 0.95rem; line-height: 1.5;">Agente: Executa tarefas, acessa sistemas com supervisão</div>
  </div>
  <div class="glass" style="padding: 1.4rem 1rem; min-height: 100px; display: flex; flex-direction: column; justify-content: center;">
    <div style="font-size: 1.1rem; font-weight: 700; color: #EC635E; margin-bottom: 0.6rem;">Nível 4</div>
    <div style="font-size: 0.95rem; line-height: 1.5;">Sistema Multiagente: Orquestra múltiplos agentes autônomos</div>
  </div>
</div>

<div class="glass mt-3" style="text-align: center; padding: 1rem;">
  <p style="font-size: 1rem; margin: 0; line-height: 1.5;">Maioria em <span style="color: #35996e; font-weight: 700;">Níveis 1 e 2</span> • Avançadas em <span style="color: #9678E8; font-weight: 700;">Nível 3</span> • <span style="color: #EC635E; font-weight: 700;">Nível 4</span> é o horizonte</p>
</div>

<style>
.slidev-page-19 .glass { padding: 1.4rem 1rem !important; }
.slidev-page-19 p { font-size: 0.95rem !important; line-height: 1.5 !important; }
</style>

<!--
"Uma das mensagens mais importantes sobre IA generativa foi a distinção de níveis de maturidade usando 4 estágios. A maioria das empresas está nos níveis 1 e 2. As mais avançadas estão chegando ao nível 3. O nível 4 — sistemas multiagentes autônomos — é o horizonte. A pergunta que fica é: em qual nível estamos no ES? E para qual nível queremos ir?"
-->

---

<!-- Slide 20 — Tendência 5: Responsible AI (Pilares) -->

# Tendência 5: Governança e Responsible AI

<div class="grid grid-cols-2 gap-2 mt-4">
  <GlassCard title="Princípios" subtitle="PILAR 1">Alinhado aos valores e cultura</GlassCard>
  <GlassCard title="Avaliação" subtitle="PILAR 2">Deve ser proporcional ao risco</GlassCard>
  <GlassCard title="Governança" subtitle="PILAR 3">Supervisão e auditoria</GlassCard>
  <GlassCard title="Educação" subtitle="PILAR 4">Capacitar a força de trabalho</GlassCard>
</div>

<style>
.slidev-page-20 .glass { padding: 0.48rem 0.8rem !important; }
.slidev-page-20 .rf-card-title { font-size: 0.9rem !important; margin-bottom: 0.2rem !important; }
.slidev-page-20 .rf-card-subtitle { margin-bottom: 0.2rem !important; font-size: 0.68rem !important; }
.slidev-page-20 p, .slidev-page-20 li { font-size: 0.8rem !important; line-height: 1.35 !important; }
</style>

<!--
"A Chevron apresentou seu framework de Responsible AI — e foi uma das palestras com maior maturidade do evento."
-->

---

<!-- Slide 20b — Responsible AI (Framework) -->

# Tendência 5: Responsible AI — Framework Chevron

<div style="display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100%; margin-top: -2rem;">
  <div style="max-height: 280px; overflow: hidden; display: flex; align-items: center; justify-content: center; width: 100%;">
    <img src="./slide8-2.png" style="width: 65%; max-width: 75%; object-fit: contain;" />
  </div>
  <div class="glass mt-3" style="text-align: center; max-width: 80%; padding: 0.5rem 0.8rem;">
    <p style="font-size: 0.9rem; font-style: italic; margin: 0; line-height: 1.4;">"Responsible AI não é freio. É o que permite <span style="color: #35996e; font-weight: 700">escalar com confiança</span>."</p>
  </div>
</div>

<!--
"A mensagem central: governança não é burocracia, é o que permite escalar com confiança. Eles têm quatro pilares: (1) princípios alinhados aos valores, (2) avaliação proporcional ao risco, (3) supervisão com responsabilidade clara, e (4) educação contínua da força de trabalho. Isso ressoa muito com o que precisamos construir aqui."
-->

---
transition: fade
hideInToc: true
---

<!-- Slide 21 — Transição: Conexão com a ES -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center" style="margin: 0; padding: 0;">
  <img src="./slide19.jpg" style="position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; margin: 0; padding: 0;" />
  <div style="position: absolute; inset: 0; background: rgba(5,15,30,0.80); margin: 0; padding: 0;"></div>
  <div class="relative z-10 px-16">
    <div class="text-xs font-mono tracking-widest mb-4" style="color: var(--rf-primary)">CONEXÃO COM O ESPÍRITO SANTO</div>
    <h1 class="font-bold text-white" style="font-size: 2.8rem; line-height: 1.3;">E o que estamos fazendo<br>no Espírito Santo?</h1>
  </div>
</div>

<style>
.slidev-page-21 { padding: 0 !important; margin: 0 !important; }
</style>

<!--
"Tudo que acabei de mostrar não está distante da nossa realidade. Muito do que vimos em Houston, já estamos construindo aqui — com nossos próprio percurso, mas ainda na mesma direção. Deixa eu mostrar o Hub de Dados e IA do Espírito Santo."
-->

---

<!-- Slide 22 — Hub de Dados e IA do ES -->

# Hub de Dados e IA — UO-ES / CSDA

<div class="flex flex-col gap-2 mt-2" style="height: calc(100% - 100px);">

<div class="glass flex items-center gap-4" style="border-left: 4px solid #35996e; padding: 0.8rem 1rem; flex: 1;">
  <div style="font-size: 1.8rem; flex-shrink: 0">🔬</div>
  <div style="flex-shrink: 0; min-width: 180px;">
    <div class="text-xs font-mono tracking-widest" style="color: var(--rf-primary); font-weight: 700; margin-bottom: 0.2rem">FRENTE 1</div>
    <div style="font-size: 0.9rem; font-weight: 700;">Análise e Ciência de Dados</div>
  </div>
  <p style="font-size: 0.75rem; line-height: 1.3; margin: 0; color: var(--rf-text); flex: 1;">Modelagem preditiva e ciência de dados aplicada às operações e subsuperfície</p>
</div>

<div class="glass flex items-center gap-4" style="border-left: 4px solid #9678E8; padding: 0.8rem 1rem; flex: 1;">
  <div style="font-size: 1.8rem; flex-shrink: 0">🤖</div>
  <div style="flex-shrink: 0; min-width: 180px;">
    <div class="text-xs font-mono tracking-widest" style="color: #9678E8; font-weight: 700; margin-bottom: 0.2rem">FRENTE 2</div>
    <div style="font-size: 0.9rem; font-weight: 700;">IA Generativa</div>
  </div>
  <p style="font-size: 0.75rem; line-height: 1.3; margin: 0; color: var(--rf-text); flex: 1;">Assistentes, RAG corporativo e automação inteligente de documentos e processos</p>
</div>

<div class="glass flex items-center gap-4" style="border-left: 4px solid #7DD5DB; padding: 0.8rem 1rem; flex: 1;">
  <div style="font-size: 1.8rem; flex-shrink: 0">📊</div>
  <div style="flex-shrink: 0; min-width: 180px;">
    <div class="text-xs font-mono tracking-widest" style="color: #7DD5DB; font-weight: 700; margin-bottom: 0.2rem">FRENTE 3</div>
    <div style="font-size: 0.9rem; font-weight: 700;">Painéis</div>
  </div>
  <p style="font-size: 0.75rem; line-height: 1.3; margin: 0; color: var(--rf-text); flex: 1;">Dashboards de gestão, produção, manutenção e indicadores estratégicos</p>
</div>

<div class="glass flex items-center gap-4" style="border-left: 4px solid #ABDB2A; padding: 0.8rem 1rem; flex: 1;">
  <div style="font-size: 1.8rem; flex-shrink: 0">⚙️</div>
  <div style="flex-shrink: 0; min-width: 180px;">
    <div class="text-xs font-mono tracking-widest" style="color: #ABDB2A; font-weight: 700; margin-bottom: 0.2rem">FRENTE 4</div>
    <div style="font-size: 0.9rem; font-weight: 700;">Automação</div>
  </div>
  <p style="font-size: 0.75rem; line-height: 1.3; margin: 0; color: var(--rf-text); flex: 1;">RPA, automação de relatórios e processos repetitivos de alto volume</p>
</div>

<div class="glass flex items-center gap-4" style="border-left: 4px solid #f59e0b; padding: 0.8rem 1rem; flex: 1;">
  <div style="font-size: 1.8rem; flex-shrink: 0">💡</div>
  <div style="flex-shrink: 0; min-width: 180px;">
    <div class="text-xs font-mono tracking-widest" style="color: #f59e0b; font-weight: 700; margin-bottom: 0.2rem">FRENTE 5</div>
    <div style="font-size: 0.9rem; font-weight: 700;">ES+Digital</div>
  </div>
  <p style="font-size: 0.75rem; line-height: 1.3; margin: 0; color: var(--rf-text); flex: 1;">Programa de inovação, cultura digital e capacitação da força de trabalho</p>
</div>

</div>


<!--
"A CSDA é o braço digital e analítico da UO-ES. Atuamos em cinco frentes: analytics e ciência de dados, IA generativa, dashboards de gestão, automação de processos — e o ES+Digital, nosso programa de inovação e cultura digital. Nos próximos slides, vou mostrar o que já temos em prática com IA generativa."
-->

---

<!-- Slide 23 — Soluções de IA Generativa na ES -->

# Soluções de IA Generativa na UO-ES

<div class="grid grid-cols-3 gap-5 mt-5">

<div class="glass text-center" style="border-top: 3px solid #35996e">
  <div class="text-xs font-mono tracking-widest mb-2" style="color: var(--rf-primary)">ASSISTENTE CORPORATIVO</div>
  <div style="font-size: 1.8rem; font-weight: 700; margin-bottom: 0.5rem">ChatGM</div>
  <Subtitle>Assistente de IA generativa para as equipes da UO-ES — RAG sobre documentos internos, políticas e dados operacionais</Subtitle>
</div>

<div class="glass text-center" style="border-top: 3px solid #9678E8">
  <div class="text-xs font-mono tracking-widest mb-2" style="color: #9678E8">MONITORAMENTO INTELIGENTE</div>
  <div style="font-size: 1.8rem; font-weight: 700; margin-bottom: 0.5rem">Farol</div>
  <Subtitle>Sistema de alertas e monitoramento de ativos com IA — detecta anomalias e prioriza ações para as equipes</Subtitle>
</div>

<div class="glass text-center" style="border-top: 3px solid #7DD5DB">
  <div class="text-xs font-mono tracking-widest mb-2" style="color: #7DD5DB">INSPEÇÃO AUMENTADA</div>
  <div style="font-size: 1.8rem; font-weight: 700; margin-bottom: 0.5rem">Farol de Inspeção</div>
  <Subtitle>IA aplicada ao workflow de inspeção — análise de imagens, geração de relatórios e priorização de intervenções</Subtitle>
</div>

</div>

<style>
.slidev-page-25 .glass { padding: 0.8rem 1.1rem !important; }
.slidev-page-25 p, .slidev-page-25 li { font-size: 0.88rem !important; line-height: 1.45 !important; }
</style>

<!--
"Aqui estão as soluções de IA generativa que desenvolvemos ou estamos desenvolvendo na UO-ES. Descrevendo cada uma: ....
E, conectando com o que vimos em Houston: não estamos só experimentando — estamos integrando IA nos fluxos de trabalho reais das equipes, exatamente como os cases que apresentei."
-->

---

<!-- Slide 24 — Conexão Houston ↔ ES -->

# Conexão Houston ↔ ES

<GlassCard title="" subtitle="🟢 ESPÍRITO SANTO" style="padding: 0.5rem 0.9rem !important;">

<div style="font-size: 0.9rem; line-height: 1.4;">

| <span style="color: #35996e; font-weight: 700;">Tendência</span> | <span style="color: #35996e; font-weight: 700;">Nossa solução</span> |
|-----------|---------------|
| Digital Twins, alertas preditivos | Ativo360 |
| RAG corporativo com dados internos | ChatPetrobras / Farol |
| IA generativa em processos | Soluções Locais |
| Diagnóstico assistido por IA | Soluções Locais |
| Cultura de dados e letramento | ES+Digital |

</div>

</GlassCard>


<style>
.slidev-page-24 .glass { padding: 0.5rem 0.9rem !important; }
.slidev-page-24 .rf-card-title { font-size: 0.9rem !important; margin-bottom: 0.3rem !important; }
.slidev-page-24 .rf-card-subtitle { margin-bottom: 0.3rem !important; font-size: 0.95rem !important; }
.slidev-page-24 td { padding: 0.25rem 0.5rem !important; font-size: 0.74rem !important; }
.slidev-page-24 th { padding: 0.25rem 0.5rem !important; font-size: 0.74rem !important; color: #35996e !important; font-weight: 700 !important; }
.slidev-page-24 p, .slidev-page-24 li { font-size: 0.77rem !important; line-height: 1.3 !important; }

.slidev-page-31 .glass { padding: 0.5rem 0.9rem !important; }
.slidev-page-31 .rf-card-subtitle { margin-bottom: 0.3rem !important; font-size: 0.95rem !important; }
.slidev-page-31 td { padding: 0.25rem 0.5rem !important; font-size: 0.74rem !important; }
.slidev-page-31 th { padding: 0.25rem 0.5rem !important; font-size: 0.74rem !important; color: #35996e !important; font-weight: 700 !important; }
.slidev-page-31 p, .slidev-page-31 li { font-size: 0.77rem !important; line-height: 1.3 !important; }
</style>

<!--
"O que me marcou no evento não foi a distância entre o que eles fazem e o que fazemos — foi a proximidade. Estamos nos mesmos desafios, com maturidade crescente em várias frentes. O que eles têm a mais é escala. E é exatamente isso que estamos construindo."
-->

---
transition: fade
---

<!-- Slide 25 — Mensagem Final -->

<div class="absolute inset-0 flex flex-col items-center justify-center px-16">

<div class="text-xl font-mono tracking-widest mb-5 text-center" style="color: var(--rf-primary)">MENSAGEM FINAL</div>

<div style="width: 100%; max-width: 760px; display: flex; flex-direction: column; gap: 0.6rem;">
  <div class="glass" style="display: flex; align-items: flex-start; gap: 1rem;">
    <span style="font-size: 1.2rem; font-weight: 700; margin-top: 0.1rem; color: var(--rf-primary); flex-shrink: 0">1</span>
    <p style="font-size: 1.05rem; font-weight: 600; color: white; line-height: 1.4; margin: 0">A IA já funciona. O desafio é escalar — e isso é organizacional.</p>
  </div>
  <div class="glass" style="display: flex; align-items: flex-start; gap: 1rem;">
    <span style="font-size: 1.2rem; font-weight: 700; margin-top: 0.1rem; color: var(--rf-primary); flex-shrink: 0">2</span>
    <p style="font-size: 1.05rem; font-weight: 600; color: white; line-height: 1.4; margin: 0">Dados de qualidade são o alicerce de tudo.</p>
  </div>
  <div class="glass" style="display: flex; align-items: flex-start; gap: 1rem;">
    <span style="font-size: 1.2rem; font-weight: 700; margin-top: 0.1rem; color: var(--rf-primary); flex-shrink: 0">3</span>
    <p style="font-size: 1.05rem; font-weight: 600; color: white; line-height: 1.4; margin: 0">IA generativa está saindo do chatbot e entrando nas operações reais.</p>
  </div>
</div>

<p style="font-size: 1rem; text-align: center; margin-top: 1.5rem; color: var(--rf-muted)">A Petrobras está nessa jornada. <span style="color: #48c790; font-weight: 700">Vamos juntos.</span></p>

</div>

<style>
.slidev-page-25 .glass { padding: 0.7rem 1.2rem !important; }
</style>

<!--
"Três mensagens para levar daqui. Primeiro: a IA já funciona — o desafio é escalar, e isso depende mais de liderança, incentivos e redesenho de processos do que de tecnologia. Segundo: dados de qualidade são o alicerce — sem isso, a IA amplifica erros. Terceiro: a IA generativa está evoluindo rápido — saindo do chatbot e entrando nas operações reais. E o ES está nessa jornada."
-->

---
transition: fade
---

<!-- Slide 26 — Encerramento -->

<div class="absolute inset-0 flex flex-col items-center justify-center text-center px-16">
  <div class="glass px-16 py-10 w-full max-w-2xl">
    <h1 class="font-bold mb-5" style="font-size: 3.5rem">Obrigado!</h1>
    <p class="text-lg mb-1" style="color: var(--rf-muted)">Ramon Moreno Ferrari</p>
    <p class="text-sm font-mono tracking-widest mb-6" style="color: var(--rf-primary)">ES/ENGP — CSDA | UO-ES</p>
    <div class="glass p-5">
      <p class="text-base italic leading-relaxed">
        Tem um problema no seu processo onde dados ou IA<br>poderiam ajudar? <strong>Procure a CSDA.</strong>
      </p>
    </div>
  </div>
</div>

<!--
"Fico à disposição para conversar sobre qualquer um desses temas. Se você tem um desafio no seu processo que acha que poderia se beneficiar de dados ou IA, a CSDA existe para isso. Obrigado!"
-->
