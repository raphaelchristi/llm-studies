# Context Engineering

Context Engineering é uma técnica avançada de engenharia de prompt que se concentra em fornecer contexto de forma automática e dinâmica para sistemas de Inteligência Artificial, especialmente em arquiteturas de agentes.

## Princípios

O artigo da Cognition.ai, "Don't Build Multi-Agents", apresenta dois princípios fundamentais para a Context Engineering:

1.  **Compartilhe o contexto e os rastreamentos completos do agente, não apenas mensagens individuais:** Para que os agentes tomem decisões consistentes, eles precisam ter acesso a todo o histórico de interações, e não apenas a mensagens isoladas.
2.  **Ações carregam decisões implícitas, e decisões conflitantes geram resultados ruins:** Cada ação de um agente é baseada em uma decisão. Se vários agentes tomam decisões conflitantes, o resultado final do sistema será prejudicado.

## Implicações

A principal implicação desses princípios é que, para a maioria dos casos de uso em 2025, a abordagem mais robusta é usar um agente linear de thread único, em vez de vários agentes colaborando. Para tarefas muito grandes, a sugestão é usar um modelo cujo objetivo principal seja comprimir um histórico de ações e conversas em detalhes, eventos e decisões importantes.

## Fonte

*   [Don't Build Multi-Agents - Cognition](https://cognition.ai/blog/dont-build-multi-agents#principles-of-context-engineering)
