# AGENTS.md — hs-desk-downloads (HS Systems)

Instruções para assistentes de código que não são o Claude Code (Codex e outros). O Claude Code recebe isto
pelo kit da equipe (repositório `hs-agentes`); aqui vai o mesmo, por escrito.

1. **Leia o `CLAUDE.md` deste repositório**, se existir: foi escrito para o Claude Code, mas vale igual para você
   (regras, comandos, armadilhas).
2. **Agentes da Central de Agentes que trabalham aqui:** **HS Desk** (manual: `docs/agentes/hsdesk.md`). Os manuais ficam no repositório `hs-agentes`:
   com o kit instalado, em `~/.claude/hs/kit/docs/agentes/`; sem o kit, em https://github.com/hs-systems-admin/hs-agentes/blob/main/docs/agentes.
3. **Passo a passo** (deploy, nova versão, atualizar cliente, alterar CLP…): `docs/procedimentos/` do `hs-agentes`.
   **Conhecimento acumulado** da equipe (decisões e armadilhas de cada projeto): `docs/conhecimento/README.md`.
   **Skills** da equipe: `skills/<nome>/SKILL.md` — leia a que servir para o trabalho.
4. **Para a equipe ver o que você está fazendo**, abra pelo lançador do kit: `hs-agente <número da tarefa> --codex`
   (o contexto da central vem em `.git/hs-contexto.md`). Ao terminar: `hs-agente concluir <número> <link do PR>`.
5. **Sem os hooks do Claude Code, a central não trava recursos para você.** Servidor de produção, bancada e
   publicação do instalador: só pelo Claude Code com o kit. Nunca desative intertravamentos de segurança da máquina.
6. Nunca escreva senhas, tokens ou endereços de servidor em arquivos. Escreva e responda em português (pt-BR).
