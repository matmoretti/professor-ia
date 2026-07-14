# 🎓 Professor IA — aprenda Claude Code e arquitetura de IA com o próprio Claude

Uma **skill de Claude Code** que transforma o Claude no seu professor particular de Claude Code e arquitetura de IA — do zero absoluto (o que é um LLM? o que é um terminal?) até construir seu próprio agente de ponta a ponta.

Feita para quem **nunca programou**: nenhum termo fica sem explicação, toda aula tem demonstração ao vivo na sua máquina, exercício prático, quiz e uma página web interativa. O progresso fica salvo entre sessões — o professor sempre lembra de onde vocês pararam.

> Este curso nasceu de uma aula real: um product designer leigo em programação pediu ao Claude que criasse uma skill para ensiná-lo. Este repositório é o resultado, generalizado para qualquer pessoa.

## O que vem dentro

- **`skill/SKILL.md`** — o professor: personalidade, metodologia e o currículo completo em 3 trilhas:
  - **Trilha 0 — Fundamentos** (sob demanda): markdown, terminal, JSON, git, APIs, arquivos.
  - **Trilha A — Claude Code na prática**: do primeiro comando a subagentes, MCP, workflows e automação.
  - **Trilha B — Arquitetura de IA**: como LLMs funcionam, anatomia de agentes, RAG, tool design, evals, segurança, custos.
  - **Projeto final**: construir um agente completo, escolhido conforme a sua profissão.
- **`skill/progresso-template.md`** — modelo do arquivo de progresso que o professor mantém sobre você.
- **`aulas/aula-01.html`** — exemplo real de aula visual interativa (Aula 1: "O autocompletar gigante").

## Como instalar

Pré-requisito: [Claude Code](https://claude.com/claude-code) instalado.

1. Baixe este repositório (botão **Code → Download ZIP**, ou `git clone`).
2. Copie o **conteúdo da pasta `skill/`** para:
   - **Windows:** `C:\Users\SEU_USUARIO\.claude\skills\professor-ia\`
   - **Mac/Linux:** `~/.claude/skills/professor-ia/`
   (Crie a pasta `professor-ia` se não existir.)
3. Abra (ou reinicie) o Claude Code e diga: **"bora estudar"** — ou invoque `/professor-ia`.

Na primeira aula o professor faz um diagnóstico rápido, cria seu arquivo de progresso e monta o portal do curso — uma página web com a grade curricular e seu avanço marcado.

## Como funciona uma aula

1. Recap da aula anterior (e cobrança carinhosa do dever de casa 😄)
2. Um conceito central, com analogia do *seu* mundo profissional
3. Demonstração ao vivo na sua máquina
4. Exercício que **você** faz
5. Quiz de verificação + página visual da aula
6. Boletim final e gancho pra próxima

## Contribuindo

Achou um erro, tem uma analogia melhor ou quer propor um módulo novo? Abra uma issue ou um pull request — este curso melhora a cada aluno.

## Licença

[MIT](LICENSE) — use, adapte e ensine à vontade.
