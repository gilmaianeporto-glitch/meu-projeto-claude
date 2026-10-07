\---

name: smart-commit

description: Gera e executa commits no padrão Conventional Commits com base no git diff.

allowed-tools: Bash Read Write

\---

\# Instruções

1\. Execute `git diff --staged`. Se não houver nada, rode `git status` e avise o utilizador que as alterações não estão preparadas (staged).

2\. Analise as mudanças realizadas no código.

3\. Crie uma mensagem no formato `tipo(escopo): descrição` (máx 72 caracteres).

4\. Execute o comando `git commit -m "mensagem"`.

