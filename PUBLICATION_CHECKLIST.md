# Portão de publicação pública

Nenhuma etapa abaixo deve ser tratada como concluída sem validação individual.

## Bloqueadores absolutos
- [ ] Zero ocorrência do nome sigiloso ou de suas variações.
- [ ] Zero referência a organizações, clientes ou informações corporativas reais.

## Conteúdo
- [ ] README e documentos revisados contra o estado técnico mais recente.
- [ ] Nenhuma capacidade futura apresentada como concluída.
- [ ] Nenhuma referência corporativa, de cliente ou dado pessoal.
- [ ] Nenhum caminho local, token, chave, segredo, IP privado ou relatório interno.
- [ ] Mockups identificados como “conceito visual, não representa a versão atual”.
- [ ] Nenhum indicativo de marca registrada antes da validação jurídica.

## Configuração do repositório
- [ ] Repositório público documental separado do repositório operacional privado.
- [ ] Branch padrão `main` protegida por ruleset.
- [ ] Force push e exclusão da `main` bloqueados.
- [ ] Secret scanning habilitado.
- [ ] Push protection habilitado.
- [ ] Private vulnerability reporting habilitado.
- [ ] Wiki desabilitada.
- [ ] Releases sem binários.
- [ ] Actions desabilitado enquanto não houver workflow revisado.
- [ ] Issues e Discussions revisadas antes da habilitação pública.

## Portão final
- [ ] Conteúdo aprovado individualmente.
- [ ] Configurações conferidas individualmente.
- [ ] Primeiro commit inspecionado antes do push.
- [ ] Nenhuma publicação externa realizada apenas por automação.