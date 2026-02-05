# 🚀 Mastering Git & GitHub: Curso Datacamp e TMW

Um curso para aprender a trabalhar com versionamento de código, repositórios remotos com GitHub, GitFlow e Visual Studio Code. Este repositório é o registro da minha jornada de especialização em controle de versão, combinando o rigor teórico do DataCamp com a abordagem prática do Teo Me Why.

# Fluxo de Trabalho Git local
1. git checkout -b
2. cria ou atualiza arquivos
3. git status
4. git add arquivos
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

# Fluxo de Trabalho GitHub <> Local
1. git clone
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

# Fluxo do Trabalho GitHub <> Local (open-source)
1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

# Aprofundamento em tópicos mais avançados
1. Diferentes tipos de Merge (fast-forward, three-way, squash, octopus e rebase).
2. Git cherry-pick, git bisect, git filter-repo, git reflog, git worktrees, git submodules e git lfs.
3. Estratégia de Ramificação Trunk-Based Developmente (TBD).

# 🧠 Estrutura do Aprendizado
- Teoria e Resumos: Centralizados no Notion, onde estruturei mapas mentais e documentação detalhada sobre estados do Git, arquitetura de sistemas distribuídos e boas práticas.

- Prática Intensiva: Exercícios focados em resolução de conflitos, manipulação de histórico e automação.

# 🛠️ O que há no repositório?
O projeto está organizado para facilitar a consulta rápida:

📁 apresentacao/: Materiais de introdução e conceitos iniciais.

📁 arquivos/: Laboratórios práticos e exercícios de versionamento.

📁 comandos/: Um guia de referência (cheatsheet) que vai do git init ao git rebase e comandos avançados.

# 🔬 Conexão com Análise de Dados
Como estudante de Relações Internacionais e aspirante a Analista de Dados, entendo que o Git é o pilar da reprodutibilidade. Este repositório serve como base para meus projetos futuros em R, Python e SQL, garantindo que cada análise seja auditável e colaborativa.

# 🤝 Contato

Linkedin: www.linkedin.com/in/pedrosolonassis
