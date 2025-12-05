# Estrutura do Livro de Agentes de IA

## Sumário Executivo
- Objetivo: guiar o leitor do nível intermediário ao especialista em agentes de IA, alinhando rigor teórico, prática de programação e experimentação científica.
- Resultado esperado: capacidade de projetar, implementar, avaliar e operacionalizar agentes reativos, deliberativos, probabilísticos, multiagentes e baseados em LLMs.
- Público-alvo: engenheiros de software, cientistas de dados e pesquisadores iniciantes com familiaridade em programação e matemática básica.

## Prefácio e Público-alvo
- **Tom editorial**: pragmático e direto, combinando teoria com implementação passo a passo.
- **Pré-requisitos**: domínio de Python, cálculo diferencial, álgebra linear e probabilidade básica.
- **Perfil do leitor**: profissionais que buscam desenvolver agentes robustos em cenários acadêmicos e de produção, valorizando reprodutibilidade e segurança.

## Mapeamento de Capítulos por Fase (referência: PHASES.md)

### Fase 0 – Pré-requisitos Técnicos
- Capítulo 0.1: Matemática essencial (grafos, probabilidade, otimização, lógica formal)
  - Seções: fundamentos, exemplos aplicados, exercícios de derivação, checklist de aprovação.
- Capítulo 0.2: Fundamentos de CS (estruturas de dados, algoritmos de busca, sistemas distribuídos, arquitetura de software)
  - Seções: estudos de caso, implementação de A* do zero, laboratório de sistemas distribuídos.
- Capítulo 0.3: Diagnóstico prático
  - Implementações guiadas: A*, Q-learning básico, transformer minimalista.
  - Exercícios de fixação com critérios autoavaliáveis.

### Fase 1 – Fundamentos Teóricos
- Capítulo 1.1: Definição formal de agentes, racionalidade e autonomia.
- Capítulo 1.2: Taxonomia de ambientes e implicações arquiteturais.
- Capítulo 1.3: Leituras guiadas e resumos críticos (Russell & Norvig, Wooldridge, paper 1995).
- Capítulo 1.4: Projeto prático – agentes em grid world (reativo, modelo, objetivo) com guia passo a passo.

### Fase 2 – Arquiteturas Fundamentais
- Capítulo 2.1: Agentes reativos e baseados em modelo; Subsumption Architecture.
- Capítulo 2.2: Planejamento clássico (STRIPS/PDDL, GraphPlan, FF/Fast Downward, heurísticas; problema do frame e ramificação).
- Capítulo 2.3: Implementação de planejador STRIPS com estudos de caso IPC.
- Capítulo 2.4: Arquitetura BDI (teoria, commitment strategies, reconsideration; uso de Jason/JACK).
- Capítulo 2.5: Arquiteturas híbridas (InteRRaP, TouringMachines, trade-offs).

### Fase 3 – Tomada de Decisão sob Incerteza
- Capítulo 3.1: MDPs (modelagem, Bellman, value/policy iteration) com exemplos codificados.
- Capítulo 3.2: RL essencial (Q-learning, DQN, PPO), tuning e estabilidade.
- Capítulo 3.3: Estudos de caso em Grid World e Inventory Management.

### Fase 4 – Planejamento Probabilístico e Dec-POMDPs
- Capítulo 4.1: POMDPs (belief states, filtros PF/KF/EKF) e métodos aproximados.
- Capítulo 4.2: Dec-POMDPs e coordenação sob incerteza; algoritmos selecionados.
- Capítulo 4.3: Aplicações em robótica móvel e assistentes virtuais.

### Fase 5 – Sistemas Multiagente
- Capítulo 5.1: Teoria de jogos e aprendizado multiagente.
- Capítulo 5.2: Comunicação explícita vs. emergente; protocolos e negociadores.
- Capítulo 5.3: Métricas de eficiência/robustez/escalabilidade; uso de simuladores (PettingZoo etc.).

### Fase 6 – LLM Agents e Ferramentas
- Capítulo 6.1: Arquitetura de agentes com LLMs (RAG, uso de ferramentas, execução de código).
- Capítulo 6.2: Observabilidade e segurança (LangSmith/Phoenix, red teaming, controle de custos).
- Capítulo 6.3: Padrões de prompts, agentes autônomos e limites práticos.

### Fase 7 – Engenharia de Produção
- Capítulo 7.1: Deploy, monitoramento, testes automatizados e experimentação controlada.
- Capítulo 7.2: Considerações de latência, custo e confiabilidade em produção.

### Fase 8 – Pesquisa e Comunidade
- Capítulo 8.1: Avaliação crítica de papers e reprodução de resultados.
- Capítulo 8.2: Contribuição open-source e participação em conferências.

### Projetos Finais
- Projeto RL complexo (PPO otimizado, curriculum learning, failure modes).
- Sistema multiagente (coordenação logística/mercado simulado; comunicação explícita vs. emergente).
- LLM agent production-grade (RAG, ferramentas, segurança, observabilidade).
- Contribuição teórica (lacuna, experimento, submissão a workshop/conferência).

### Recursos e Apêndices
- Listas de livros, cursos, plataformas de prática e comunidades.
- Cronograma sugerido (12–18 meses) e métricas de sucesso em checklist.

## Padrão de Formatação
- **Figuras**: numeradas por capítulo (Figura X.Y), com legenda curta e referência no texto.
- **Caixas de destaque**: notas de alerta, boas práticas, pitfalls e atalhos de implementação; usar blocos intitulados "Destaque".
- **Checklists de aprendizado**: ao final de cada capítulo, itens verificáveis que refletem competências práticas e teóricas.
- **Exemplos de código**: em Python, com blocos reproduzíveis, seeds fixas e referência a repositórios de apoio quando aplicável.
- **Exercícios e projetos**: tabelas com dificuldade, objetivo, critérios de avaliação e tempo estimado.
- **Referências**: padrões ABNT simplificados; incluir DOI ou URL persistente.

## Fluxo de Revisão
- Cada capítulo deve passar por revisão técnica (conteúdo) e editorial (clareza e coesão).
- Versões alpha → beta → release candidate, com checklist de reprodutibilidade (scripts, dados, seeds).

