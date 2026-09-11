<div align="center">
  <img src="assets/branding/anonymous-symbol-primary.png" width="180" alt="Símbolo abstrato do projeto experimental">

# Projeto experimental de supervisão de agentes
### Supervisão humana para agentes de IA em um aplicativo desktop

**Projeto autoral de pesquisa aplicada em orquestração segura, rastreável e supervisionada de agentes de IA.**

[Visão](docs/VISION.md) · [Arquitetura](docs/ARCHITECTURE.md) · [Status](docs/STATUS.md) · [Roadmap](docs/ROADMAP.md) · [Parcerias](PARTNERSHIPS.md) · [English](README.en.md)
</div>

> [!IMPORTANT]
> O projeto está em desenvolvimento ativo. Este repositório é uma vitrine pública e documental. Não distribui código-fonte nem instalador e não promete disponibilidade para produção.
## O problema

Modelos de IA conseguem sugerir planos, código e automações. Porém, transformar respostas em ações reais exige controle de contexto, aprovação humana, limites de risco, rastreabilidade, validação e capacidade de interromper ou reverter uma execução.

## A proposta

O projeto explora uma camada de supervisão entre pessoas, modelos e ferramentas de execução:

```text
Objetivo humano
      ↓
Missão estruturada
      ↓
Análise de risco e contrato
      ↓
Aprovação humana
      ↓
Modelo ou agente autorizado
      ↓
Executor controlado
      ↓
Testes, evidências e resultado
```

A visão é permitir que diferentes inteligências, locais ou em nuvem, sejam escolhidas conforme privacidade, custo, capacidade e risco, sem entregar controle irrestrito ao modelo.

## O que já foi demonstrado

- aplicativo experimental em janela própria no Windows;
- fluxo supervisionado de criação, submissão, aprovação, fila e execução;
- persistência local de missões;
- integração experimental com modelo local via Ollama;
- execução real de missão com supervisão humana;
- testes automatizados de motor e interface;
- serviços locais observados em endereços de loopback;
- processo de instalação em desenvolvimento e sob validação independente.

## O que ainda não está pronto

- distribuição pública;
- garantia de prontidão para produção;
- instalador final assinado e validado em ambientes independentes;
- integração pública com provedores de nuvem;
- autonomia ampla para aplicar código ou comandos;
- auditoria independente completa de segurança;
- disponibilidade comercial.

Consulte o [status verificável](docs/STATUS.md) e as [limitações conhecidas](docs/LIMITATIONS.md).

## Engenharia assistida por IA, com responsabilidade humana

O projeto é conduzido por Cristiano Silva como projeto autoral. O desenvolvimento utiliza vibe coding e múltiplas ferramentas de IA para apoiar pesquisa, geração de código, testes, documentação e diagnóstico.

A autoria do projeto está na definição do problema, arquitetura, requisitos, governança, decisões, integração, validação e responsabilidade pelo resultado. Saídas produzidas por IA não são aceitas apenas porque declaram sucesso: precisam de evidências, testes e revisão humana.

Leia a declaração completa em [Desenvolvimento assistido por IA](docs/AI_ASSISTED_DEVELOPMENT.md).

## Segurança desde a concepção

Princípios atuais:

- aprovação proporcional ao risco;
- privilégio mínimo;
- execução local quando apropriado;
- uso de APIs oficiais para provedores externos;
- segredos fora do repositório;
- portas locais restritas ao loopback;
- separação planejada entre programa e dados;
- logs e evidências sanitizados;
- nenhuma alegação de segurança absoluta.

Vulnerabilidades devem ser reportadas de acordo com [SECURITY.md](SECURITY.md), sem publicação de detalhes exploráveis.

## Tecnologias em experimentação

`Python` · `PowerShell 7` · `Node.js` · `Electron` · `SQLite` · `Ollama` · `GitHub Actions` · `Windows`

A presença nesta lista representa uso ou avaliação técnica. Não implica parceria, endosso ou integração concluída.

## Para quem este projeto pode interessar

- profissionais de segurança e governança de IA;
- pessoas pesquisando sistemas multiagentes;
- especialistas em aplicações desktop e automação;
- pesquisadores de interação humano-agente;
- parceiros técnicos interessados em execução segura;
- mentores, aceleradoras e investidores em estágio inicial.

## Oportunidades de colaboração

O projeto busca conversas responsáveis com pessoas que possam contribuir em:

- arquitetura de agentes e roteamento de modelos;
- sandboxing e segurança de executores;
- experiência desktop e design de produto;
- empacotamento e atualização segura no Windows;
- pesquisa aplicada, avaliação e observabilidade;
- estratégia de produto, propriedade intelectual e validação de mercado.

Consulte [PARTNERSHIPS.md](PARTNERSHIPS.md). Não envie segredos, propostas confidenciais ou dados pessoais por issues públicas.

## Transparência

- **Estágio:** pesquisa e desenvolvimento, protótipo funcional.
- **Código:** privado neste estágio.
- **Instalador:** não disponível publicamente.
- **Interface conceitual:** qualquer mockup será identificado como conceito.
- **Investimento:** abertura para conversas exploratórias, sem oferta pública de valores mobiliários.
- **Identidade pública:** provisória e descritiva, sujeita a validações formais.

## Acompanhe a evolução

Use **Watch** para acompanhar atualizações documentais e **Discussions** para conversas públicas quando habilitadas. Marcos técnicos serão publicados apenas depois de validados.

---

<div align="center">

**Projeto experimental de supervisão de agentes** · IA com limites claros, rastreabilidade e supervisão humana.

Copyright © 2026 Cristiano Silva. Todos os direitos reservados.

</div>
