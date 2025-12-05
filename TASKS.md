# Plano de Execução para o Livro de Agentes de IA

## Objetivo
Criar um livro completo em português que siga rigorosamente as fases e tópicos de **PHASES.md**, desenvolvendo o leitor até o nível de especialista em agentes de IA.

## Convenções de Controle
- [ ] = não iniciado
- [~] = em progresso
- [x] = concluído
- Cada fase terá subentregas: planejamento de capítulos, redação, exercícios/projetos, revisão técnica.

## Macrocronograma
- **Fase 0-1:** Fundamentos técnicos e conceituais — elaborar capítulos teóricos, implementações exemplo e exercícios diagnósticos.
- **Fase 2-3:** Arquiteturas e decisão sob incerteza — arquiteturas reativas/BDI/híbridas, MDPs e RL.
- **Fase 4-5:** Multiagentes e LLM agents — coordenação, comunicação, ferramentas, segurança.
- **Fase 6-7:** Operacionalização e pesquisa avançada — observabilidade, testes, papers recentes.
- **Projetos Finais:** Demonstração de maestria, estudos de caso completos.

## Tarefas Detalhadas
1. [x] **Estrutura do Livro**
   - Definir sumário executivo, prefácio e público-alvo.
   - Mapear capítulos para cada fase de PHASES.md, incluindo seções teóricas, exemplos de código e leituras.
   - Estabelecer padrão de formatação: figuras, caixas de destaque, checklists de aprendizado.

2. [ ] **Fase 0 – Pré-requisitos Técnicos**
   - Redigir capítulos sobre matemática (grafos, probabilidade, otimização, lógica) e CS (estruturas, algoritmos, sistemas distribuídos, arquitetura de software).
   - Criar tutoriais práticos: implementação de A*, Q-learning básico e transformer simples do zero.
   - Incluir exercícios de fixação e critérios de aprovação autoavaliáveis.

3. [ ] **Fase 1 – Fundamentos Teóricos**
   - Capítulo de definição formal de agentes, racionalidade vs. optimalidade, autonomia.
   - Diferenciar sistemas reativos, deliberativos e funções sem estado.
   - Elaborar leituras guiadas (Russell & Norvig, Wooldridge, paper 1995) com resumos críticos.
   - Projeto prático: agentes em grid world (reativo, baseado em modelo, baseado em objetivo) com implementação passo a passo.

4. [ ] **Fase 2 – Arquiteturas Fundamentais**
   - Redigir seções sobre agentes reativos/model-based, Subsumption Architecture.
   - Planejamento clássico: STRIPS/PDDL, GraphPlan, FF/Fast Downward, heurísticas; discutir problema do frame e ramificação.
   - Implementar planejador STRIPS básico e estudos de caso IPC.
   - Arquitetura BDI: teoria (Beliefs, Desires, Intentions, modal logic), commitment strategies, reconsideration; guias de uso Jason/JACK.
   - Arquiteturas híbridas: InteRRaP, TouringMachines; discutir trade-offs.

5. [ ] **Fase 3 – Tomada de Decisão sob Incerteza**
   - MDPs: estados, ações, transições, recompensas, equações de Bellman; value/policy iteration com exemplos.
   - RL: expandir algoritmos essenciais (Q-learning, DQN, PPO), tuning e análise de estabilidade.
   - Estudos de caso em Grid World e Inventory Management com código.

6. [ ] **Fase 4 – Planejamento Probabilístico e Dec-POMDPs**
   - Introduzir POMDPs, belief states, filtros (PF, KF, EKF), solução aproximada.
   - Dec-POMDPs e coordenação sob incerteza; algoritmos relevantes.
   - Exercícios aplicados a robótica móvel e assistentes virtuais.

7. [ ] **Fase 5 – Sistemas Multiagente**
   - Fundamentos de teoria de jogos e aprendizado multiagente.
   - Comunicação explícita vs. emergente; protocolos e negociadores.
   - Métricas de eficiência, robustez e escalabilidade; simuladores (PettingZoo etc.).

8. [ ] **Fase 6 – LLM Agents e Ferramentas**
   - Arquitetura de agentes com LLMs: RAG, tool use, code execution.
   - Observabilidade e segurança: LangSmith/Phoenix, red teaming, controle de custos.
   - Padrões de prompts, agentes autônomos e limites práticos.

9. [ ] **Fase 7 – Engenharia de Produção**
   - Deploy, monitoramento, testes automatizados, experimentação controlada.
   - Considerações de latência, custo e confiabilidade.

10. [ ] **Fase 8 – Pesquisa e Comunidade**
    - Estratégias para avaliar papers recentes, reproduzir resultados e propor melhorias.
    - Roteiro para contribuição open-source e participação em conferências.

11. [ ] **Projetos Finais**
    - Projeto RL complexo (PPO otimizado, curriculum learning, failure modes).
    - Sistema multiagente (coordenação logística/mercado simulado; comunicação explícita vs. emergente).
    - LLM agent production-grade (RAG, ferramentas, segurança, observabilidade).
    - Contribuição teórica (identificar lacuna, desenhar experimento, submissão a workshop/conferência).

12. [ ] **Recursos e Apêndices**
    - Compilar listas de livros, cursos, plataformas de prática e comunidades.
    - Incluir cronograma sugerido (12-18 meses) e métricas de sucesso como checklist final.

13. [ ] **Revisão e Qualidade**
    - Revisão técnica por fase, verificação de precisão e consistência.
    - Revisão editorial (clareza, coesão, exemplos reproduzíveis).
    - Preparar versão final e sumário executivo.

## Estado Atual
- Livro ainda não iniciado. Todas as tarefas estão abertas.

## Próximos Passos Imediatos
- Validar este plano com o solicitante.
- Após confirmação, iniciar Tarefa 1 (estrutura do livro) e avançar fase a fase conforme PHASES.md.
