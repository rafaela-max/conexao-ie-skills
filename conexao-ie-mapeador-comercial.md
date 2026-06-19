---
name: conexao-ie-mapeador-comercial
description: "Qualifica leads e apoia o processo de discovery comercial da Conexão IE. Use esta skill sempre que precisar: (1) classificar uma empresa ou lista de leads por fit e potencial, (2) identificar qual serviço da Conexão IE faz mais sentido para um perfil de empresa, (3) gerar a ficha de inteligência pré-reunião, (4) selecionar as perguntas de discovery mais relevantes para aquele perfil, (5) registrar e pontuar o resultado de uma reunião. Acione também quando o usuário mencionar 'qual produto oferecer', 'preparar reunião', 'qualificar lead', 'analisar empresa', 'montar ficha', 'perguntas para discovery', 'classificar oportunidade', 'tier A B C' ou qualquer variação disso."
---

# conexao-ie-mapeador-comercial

Qualifica leads e apoia o processo de discovery comercial da Conexão IE. Use esta skill sempre que precisar: (1) classificar uma empresa ou lista de leads por fit e potencial, (2) identificar qual serviço da Conexão IE faz mais sentido para um perfil de empresa, (3) gerar a ficha de inteligência pré-reunião, (4) selecionar as perguntas de discovery mais relevantes para aquele perfil, (5) registrar e pontuar o resultado de uma reunião. Acione também quando o usuário mencionar 'qual produto oferecer', 'preparar reunião', 'qualificar lead', 'analisar empresa', 'montar ficha', 'perguntas para discovery', 'classificar oportunidade', 'tier A B C' ou qualquer variação disso.

---

## Conexão IE · Mapeador Comercial

### O que esta skill faz

Dado o perfil de uma empresa e o cargo do contato, esta skill:

- Gera a ficha de inteligência pré-reunião preenchida com os dados disponíveis
- Define a hipótese de produto de entrada mais provável com justificativa
- Seleciona as perguntas de discovery prioritárias para confirmar ou refutar essa hipótese
- Classifica o lead em Tier A, B ou C
- Sinaliza alertas de baixo fit (feudo, porte insuficiente, segmento bloqueado)
- Registra o resultado pós-reunião quando solicitado

---

### Inputs esperados

**Mínimo obrigatório:**
- Nome da empresa
- Segmento / setor
- Estimativa de porte (nº de funcionários — LinkedIn, site ou declarado)
- Cargo e nome do contato
- Como o contato chegou até a Conexão IE (evento, indicação, busca ativa)
- Interesse declarado (se houver)

**Complementar (melhora a entrega):**
- Histórico com a Conexão IE (já foi cliente, proposta anterior, contato antigo)
- Localização da empresa
- Presença de universidade corporativa ou consultor fixo instalado
- Transcrição ou resumo de conversa anterior com o contato
- Planilha de leads (aceita .xlsx ou .csv para análise em lote)

---

### Contexto da Conexão IE

**Quem são**

Empresa brasileira com 18 anos de atuação em inteligência emocional e desenvolvimento humano para organizações. Fundada por Alessandra Gonzaga (doutora em Gestão de Pessoas, autoridade técnica em IE) e Marcelo do Carmo (engenharia de processos e operação comercial).

Diferencial: parte do perfil emocional de cada pessoa para gerar desenvolvimento mais assertivo. Não existe solução prateleira — cada programa é desenhado a partir de um assessment comportamental.

---

### Portfólio de produtos

**LAB IE (Laboratório Comportamental)**
Produto de entrada pelo time. Sempre começa com assessment (Profiler ou PDA), seguido de reunião com RH, devolutiva para o time e workshop. O conteúdo do workshop é definido pelo cliente — autoconhecimento, IE, segurança psicológica, alta performance, vendas, entre outros. Faixa: R$ 12k a R$ 24k (varia por participantes, horas e formato).

**Mentoria Executiva e Análise Executiva**
Entrada pela alta liderança. Conduzida pela Alessandra. A Análise Executiva é individual com o líder e o Profiler. A Mentoria Executiva envolve RH e, em alguns casos, o time do líder. Estratégica porque abre caminho para vender serviços para o time depois. Faixa: negociável conforme escopo.

**Liderança em Movimento (Náutilus)**
Arquitetura de transformação em três níveis:
- 90°: líder com o seu time
- 180°: alinhamento entre líderes de áreas diferentes que não se conversam
- 360°: organização inteira — direção, lideranças e equipes. Para mudanças culturais ou de grande porte.
Faixa 360°: R$ 90k a R$ 200k / 3 a 6 meses.

**Conectados**
Baseado no livro da Conexão IE. Do clube do livro com quatro lives até imersão com assessment. Modelo próprio com pilares de autoconhecimento, equilíbrio emocional, conexões humanas e trabalho com significado. Ativado quando o cliente demonstra interesse específico no livro ou modelo.

**GAP IE (Jornada de Gestão de Atenção Psicossocial)**
Voltado para empresas que precisam responder à NR-1. Organiza as ações em três fatores: Trabalho e Carga, Gestão e Organização, Relações e Segurança. Ativado principalmente para indústrias e saúde com mais de 100 funcionários.

---

### Lógica de produto por perfil

> Sem discovery, não há produto definitivo. A hipótese abaixo é ponto de partida, não diagnóstico fechado.

```
Contato é C-level ou Diretoria?
├── Sim → Hipótese: Mentoria Executiva
│         Alessandra conduz. Abre caminho para o time depois.
│
└── Não → A dor é compliance ou NR-1?
          ├── Sim (indústria ou saúde, +100 func.) → Hipótese: GAP IE
          │   Confirmar se já fizeram levantamento de riscos.
          │
          └── Não → Qual é a natureza da dor de liderança?
                    ├── Líder com o time → Hipótese: LAB IE
                    │   Mais versátil. Assessment + RH + devolutiva + workshop.
                    │
                    ├── Líderes entre si (áreas que não se conversam)
                    │   → Hipótese: Liderança em Movimento 180°
                    │
                    └── Transformação cultural ampla
                        → Hipótese: Liderança em Movimento 360°
                        Apenas após discovery aprofundada.
```

Conectados entra quando o cliente demonstrou interesse específico no livro ou modelo — não é produto de entrada padrão.

---

### Perfil de cliente ideal (ICP)

**Alto fit:**
- 100+ funcionários (preferencialmente 200+)
- Segmentos com maior histórico: indústria metalúrgica, química, alimentos, saúde corporativa, judiciário, cooperativas
- Contatos: diretores de RH, gestores de DHO, CEOs e diretores com autonomia para decidir
- Empresas em transição (fusão, sucessão, crescimento acelerado, mudança cultural) — dor mais urgente, ciclo mais rápido

**Baixo fit — sinalizar alerta:**
- Menos de 100 funcionários
- Consultor fixo ou universidade corporativa instalada ("feudo") — ex: Tramontina, Randon, Sicredi/Nortus
- Segmento sem histórico de compra de IE

---

### Ficha de inteligência pré-reunião

Ao rodar esta skill, gerar a ficha abaixo preenchida com os dados disponíveis. Campos sem dado marcados como [investigar na discovery].

```
FICHA PRÉ-REUNIÃO | CONEXÃO IE

--- EMPRESA ---
Nome:
Segmento:
Porte (nº funcionários):
Localização:
Site:
Universidade corporativa ou consultor fixo: [ ] Sim [ ] Não [ ] Investigar

--- CONTATO ---
Nome:
Cargo:
Nível: [ ] C-level/Diretoria [ ] Gerência [ ] RH operacional [ ] Outro
Perfil: [ ] Decisor [ ] Influenciador [ ] Não mapeado
Como chegou: [ ] Evento [ ] Indicação [ ] Busca ativa [ ] Já era contato
Já conhecia a Conexão IE ou Alessandra: [ ] Sim [ ] Não [ ] Parcialmente

--- INTERESSE DECLARADO ---
[ ] Reunião [ ] LAB IE [ ] Conectados [ ] Profiler/PDA
[ ] NR-1 / GAP IE [ ] Mentoria [ ] Outro: ______

--- HIPÓTESE ---
Dor provável:
[ ] NR-1 / compliance psicossocial
[ ] Liderança individual
[ ] Alinhamento entre líderes
[ ] Cultura / transformação organizacional
[ ] Não identificada

Produto de entrada hipotético:
[ ] LAB IE [ ] Mentoria Executiva [ ] Conectados
[ ] Liderança em Movimento 90° [ ] Liderança em Movimento 180°
[ ] Liderança em Movimento 360° [ ] GAP IE

Base da hipótese:

--- ALERTAS ---
[ ] Menos de 100 funcionários
[ ] Feudo instalado — qual:
[ ] Segmento bloqueado

--- HISTÓRICO ---
Já foi cliente: [ ] Sim [ ] Não [ ] Contato anterior sem fechamento
Serviço e período (se sim):

--- CLASSIFICAÇÃO ---
Tier: [ ] A — alta prioridade [ ] B — médio potencial [ ] C — baixo potencial
Participação AN1 na reunião: [ ] Sim [ ] Não
```

---

### Roteiro de discovery (perguntas selecionadas por perfil)

> Não entregar o roteiro completo de uma vez. Selecionar apenas as perguntas relevantes para o perfil mapeado.

**Abertura (sempre)**
"Antes de qualquer coisa, quero entender um pouco mais sobre você e a empresa. Me conta: como é que tá o momento de vocês hoje?"

**Bloco 1 — Contexto da empresa**
- "Quantas pessoas têm na empresa hoje?"
- "Você tem lideranças intermediárias, tipo coordenadores e gerentes, ou é mais direto da direção para o time?"
- "Vocês já têm algum programa de desenvolvimento de pessoas rodando ou é algo que ainda não acontece de forma estruturada?"

**Bloco 2 — Dor ativa (sempre)**
- "O que te trouxe até a palestra? O que chamou atenção?"
- "Se eu te pedir para me contar o maior desafio com as pessoas da empresa agora, o que você me diria?"
- "Isso é mais um problema do líder com o time dele ou é mais entre líderes — áreas que não se conversam?" → Resposta define LAB IE (líder + time) vs Liderança em Movimento 180° (líderes entre si)

**Bloco 3 — NR-1 (ativar só para indústria/saúde ou se cliente trouxer o tema)**
- "A NR-1 já está no radar de vocês ou ainda não chegou como prioridade?"
- "Vocês já fizeram o levantamento de riscos psicossociais ou estão ainda nessa fase?" → Sim para as duas: GAP IE entra antes do LAB IE

**Bloco 4 — Urgência e decisão (sempre)**
- "Isso é uma prioridade para agora ou ainda está em fase de avaliação?"
- "Quando vocês pensam em investir em algo assim, essa decisão passa por você ou envolve outras pessoas?"
- "Tem alguma janela de orçamento que vocês já estejam olhando para isso?"

**Fechamento**
- Decisor: "Com base no que você me contou, eu consigo montar algo bem direcionado para o caso de vocês. Faz sentido eu te enviar uma proposta até [data]?"
- Influenciador: "Faz sentido a gente marcar um momento com [decisor] junto, para eu entender melhor o contexto antes de montar a proposta?"

---

### Registro pós-reunião

Quando solicitado após uma reunião, preencher e retornar:

```
Dor confirmada ou diferente da hipótese:
Produto que faz sentido oferecer:
Quem decide e se já está mapeado:
Urgência real: [ ] Agora [ ] Próximo semestre [ ] Sem definição
Próximo passo combinado e data:
```

---

### Classificação de tier

| Tier | Critérios |
|------|-----------|
| A | 100+ funcionários, decisor ou influenciador de peso, dor clara, urgência no semestre |
| B | Fit parcial, urgência incerta, vale nutrir e acompanhar |
| C | Menos de 100 func., feudo instalado ou sem dor clara — ação mínima |

---

### Como ativar esta skill

Comandos naturais que ativam a skill:
- `/conexao-ie-mapeador-comercial` seguido do contexto da empresa
- "Qualifica [empresa] para mim"
- "Monta a ficha de [empresa]"
- "Qual produto faz mais sentido para [perfil]?"
- "Prepara a reunião com [empresa]"
- "Analisa essa lista de leads" (com planilha anexada)

---

### Expansão planejada (versão 2.0)

- Faixas de preço confirmadas para Mentoria Executiva, GAP IE e Conectados
- Lógica de upsell por produto (o que vem depois de cada entrada)
- Padrão de dor por segmento validado em campo
- Histórico de clientes por setor para prova social na discovery
- Perguntas específicas por segmento
- Scoring numérico (0 a 15) por porte, dor e urgência

> Atualizar esta skill com: "Quero atualizar a skill conexao-ie-mapeador-comercial. [o que mudou]"
