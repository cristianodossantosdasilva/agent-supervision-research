# Configuração recomendada do repositório

## Identidade

- Nome sugerido: `agent-supervision-research`
- Descrição: `Pesquisa aplicada em orquestração supervisionada de agentes de IA para desktop.`
- Visibilidade: pública
- Código operacional: não incluir
- Releases: desabilitadas ou sem binários neste estágio

## Topics sugeridos

`ai-agents` `multi-agent-systems` `human-in-the-loop` `ai-governance` `cybersecurity` `desktop-app` `electron` `python` `powershell` `vibe-coding` `responsible-ai`

## Segurança

- habilitar secret scanning;
- habilitar push protection;
- habilitar Dependabot alerts se houver manifests de dependência no futuro;
- habilitar private vulnerability reporting;
- proteger a branch `main` com ruleset ativo, bloqueio de force push e exclusão;
- exigir pull request para mudanças públicas relevantes; enquanto houver apenas um mantenedor, não exigir aprovação impossível do próprio autor;
- manter GitHub Actions desabilitado enquanto não houver workflow revisado; se habilitado no futuro, usar permissões mínimas;
- habilitar Discussions somente após revisar categorias, mensagem de boas-vindas e regras de moderação;
- desabilitar Wikis se não forem usadas.

## Regra de publicação

Nenhum arquivo deve ser copiado diretamente do repositório operacional privado. Toda publicação deve passar por curadoria e sanitização específica.
