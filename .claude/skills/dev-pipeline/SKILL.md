\---

name: dev-pipeline

description: Orquestrador do fluxo completo de desenvolvimento.

allowed-tools: Bash Read Write

\---

\# Instruções

Quando esta skill for ativada, execute os passos na seguinte ordem:

1\. Primeiro, chame a skill de `code-review`.

2\. Se passar na revisão, acione a skill `smart-commit`.

3\. Por fim, atualize as documentações chamando a skill `changelog`.

