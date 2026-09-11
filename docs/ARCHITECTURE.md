# Arquitetura conceitual

```text
Mission Control Desktop
        │
        ├── Missões e aprovações
        ├── Políticas de risco, custo e privacidade
        ├── Memória e evidências
        │
        └── Roteador
             ├── Modelos locais
             ├── APIs oficiais de modelos em nuvem
             ├── Agentes autorizados
             └── Executores controlados
                    ├── PowerShell
                    ├── Git
                    ├── Arquivos
                    └── Testes
```

## Separações importantes

- **Modelo:** produz análise ou proposta.
- **Agente:** planeja e usa ferramentas dentro de um escopo.
- **Executor:** aplica ações autorizadas.
- **Mission Control:** registra, governa, supervisiona e apresenta evidências.

Este documento é conceitual e omite detalhes internos, controles defensivos específicos e implementação proprietária.
