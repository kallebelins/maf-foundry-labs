# MAF Foundry Labs

Laboratórios práticos sobre **Microsoft Agent Framework (MAF)**, **Azure AI Foundry**, agentes, workflows, automações inteligentes e padrões modernos para construção de soluções agentic em .NET.

Este repositório nasceu com um objetivo simples:

> Aprender, experimentar e documentar, na prática, como construir aplicações modernas baseadas em agentes, workflows, ferramentas, automação e inteligência artificial aplicada a cenários reais.

Aqui você encontrará uma jornada progressiva de estudos, experimentos e demonstrações práticas envolvendo MAF, Foundry, agentes, workflows declarativos, integrações, observabilidade, resiliência e padrões arquiteturais para soluções inteligentes.

---

## Por que este repositório existe?

A inteligência artificial deixou de ser apenas uma chamada para um modelo de linguagem.

Hoje, construir soluções realmente úteis exige muito mais:

- Orquestrar agentes especializados;
- Criar workflows controláveis;
- Integrar ferramentas externas;
- Manter rastreabilidade;
- Permitir intervenção humana;
- Registrar decisões;
- Observar execuções;
- Lidar com falhas;
- Automatizar tarefas reais;
- Conectar IA com processos de negócio.

O **Microsoft Agent Framework** e o **Azure AI Foundry** surgem como peças importantes nesse novo cenário, permitindo construir sistemas agentic mais organizados, observáveis e preparados para ambientes corporativos.

Este repositório é uma tentativa prática de responder perguntas como:

- Como sair de um chatbot simples para um workflow inteligente?
- Como transformar agentes em componentes reutilizáveis?
- Como executar fluxos com decisões, loops, paralelismo e estado?
- Como conectar agentes a ferramentas reais?
- Como criar processos com aprovação humana?
- Como observar, testar e evoluir soluções agentic?
- Como aplicar esses conceitos em uma futura fábrica de software com IA?

---

## O que você vai encontrar aqui

Este repositório será construído em formato de **laboratórios práticos**, cada um explorando um conceito específico.

Cada laboratório será pensado para ser:

- Simples o suficiente para ser entendido;
- Prático o suficiente para ser executado;
- Documentado o suficiente para ser estudado;
- Evolutivo o suficiente para servir como base para soluções maiores.

A ideia não é apenas mostrar código funcionando.

A ideia é explicar o raciocínio por trás de cada implementação, os aprendizados, os problemas encontrados, as decisões técnicas e os padrões que podem ser reutilizados em projetos reais.

---

## Principais temas abordados

Os laboratórios serão organizados por grandes áreas de aprendizado.

### Core Workflow Concepts

Fundamentos de workflows no Microsoft Agent Framework.

Aqui serão explorados conceitos como execução, transições, eventos, roteamento, condições, loops, paralelismo e agregação de resultados.

Essa é a base para entender como um processo inteligente pode deixar de ser uma sequência rígida de chamadas e passar a ser um fluxo controlado, observável e adaptável.

---

### State and Persistence

Laboratórios voltados para estado, persistência e continuidade.

Soluções agentic reais precisam lembrar informações durante a execução, compartilhar dados entre etapas, recuperar falhas e continuar processos interrompidos.

Essa categoria explora como manter contexto e estado de forma mais organizada.

---

### Human Interaction

Nem todo processo deve ser 100% autônomo.

Em muitos cenários, o humano precisa revisar, aprovar, corrigir, complementar ou decidir.

Aqui entram padrões de **human-in-the-loop**, aprovações, entradas externas e pontos de controle humano dentro de workflows inteligentes.

---

### Observability

Agentes sem observabilidade viram caixas-pretas.

Esta categoria explora como registrar eventos, acompanhar execuções, gerar métricas, usar tracing e entender o comportamento dos fluxos.

O objetivo é tornar a execução dos agentes mais transparente, auditável e confiável.

---

### Visualization

Workflows inteligentes podem ficar complexos rapidamente.

Por isso, visualizar fluxos é essencial.

Aqui serão exploradas formas de representar workflows como diagramas, facilitando entendimento técnico, documentação, revisão de arquitetura e comunicação com times.

---

### Agent Integration

Laboratórios focados na criação e integração de agentes.

Essa categoria explora agentes simples, agentes com ferramentas, agentes dentro de workflows, respostas estruturadas, middleware e integração com serviços externos.

É aqui que começamos a sair do fluxo tradicional e entramos de fato no mundo dos sistemas agentic.

---

### Azure AI Foundry

Laboratórios voltados à integração com o Azure AI Foundry.

A proposta é experimentar agentes hospedados, configurações, ferramentas, provisionamento, chamadas a agentes e integração com workflows do MAF.

Essa parte é essencial para entender como combinar desenvolvimento local, orquestração em .NET e agentes hospedados em ambiente cloud.

---

### Declarative Workflows

Um dos pontos mais interessantes do MAF é a possibilidade de definir workflows de forma declarativa.

Essa categoria explora o uso de arquivos declarativos para representar fluxos, variáveis, condições, chamadas a agentes, aprovações e pipelines mais completos.

A ideia é estudar como separar definição de processo da implementação técnica.

---

### Advanced Patterns

Aqui entram padrões mais avançados de colaboração entre agentes e workflows.

Serão explorados conceitos como revisão iterativa, múltiplos agentes colaborando, subworkflows, composição hierárquica e workflows encapsulados como componentes reutilizáveis.

Essa categoria ajuda a evoluir de exemplos simples para arquiteturas mais próximas de sistemas reais.

---

### Resilience

Soluções reais falham.

APIs ficam indisponíveis, ferramentas retornam erro, modelos podem responder fora do esperado, integrações podem expirar e processos podem ser interrompidos.

Esta categoria explora padrões de resiliência, tratamento de erro, retry, compensação, timeout e recuperação.

---

### Deployment

Depois que um laboratório funciona localmente, surge outra pergunta:

> Como executar isso em ambiente real?

Aqui serão exploradas possibilidades de hospedagem, execução em APIs, funções serverless, containers, automações e integração com pipelines.

O objetivo é aproximar os experimentos de cenários de produção.

---

### Reasoning

Esta categoria explora padrões de raciocínio estruturado e planejamento externo.

O foco não é expor raciocínio interno de modelos, mas criar artefatos observáveis de decisão, planejamento, reflexão, análise, grafos de conhecimento e estratégias de execução.

A proposta é estudar como agentes podem produzir saídas mais organizadas, verificáveis e úteis para processos complexos.

---

### Software Factory

Esta é uma das categorias mais importantes do repositório.

Aqui os conceitos anteriores começam a se unir em uma visão maior: uma fábrica de software orientada por agentes, especificações, revisão, geração de código, testes, aprovação humana e rastreabilidade.

A ideia é explorar, passo a passo, como agentes podem apoiar atividades como:

- Análise de requisitos;
- Decomposição de funcionalidades;
- Escrita de especificações;
- Revisão técnica;
- Decisões arquiteturais;
- Geração de código;
- Revisão de código;
- Execução de testes;
- Aprovação antes de merge;
- Pipeline completo de desenvolvimento assistido por IA.

---

## O que cada laboratório deve entregar

Cada laboratório será acompanhado, sempre que fizer sentido, por documentação explicando:

- Objetivo do laboratório;
- Conceito explorado;
- Como executar;
- Principais arquivos;
- Explicação do fluxo;
- Pontos de atenção;
- Aprendizados;
- Possíveis melhorias;
- Relação com cenários reais.

O objetivo é que cada laboratório seja útil tanto para quem quer apenas assistir ao vídeo quanto para quem deseja clonar o repositório e executar os exemplos.

---

## Para quem este repositório é indicado?

Este conteúdo é indicado para:

- Desenvolvedores .NET interessados em IA;
- Arquitetos de software;
- Engenheiros de IA;
- Pessoas estudando agentes inteligentes;
- Profissionais interessados em Azure AI Foundry;
- Times que desejam entender workflows agentic;
- Pessoas que querem sair do chatbot simples e construir sistemas inteligentes mais robustos;
- Quem deseja criar automações com agentes, ferramentas e intervenção humana;
- Quem está estudando o futuro da engenharia de software com IA.

---

## Filosofia dos laboratórios

Este repositório segue alguns princípios.

### Clareza antes de complexidade

Cada laboratório deve ensinar bem uma ideia antes de misturar muitos conceitos.

### Evolução progressiva

Os exemplos devem crescer aos poucos, permitindo entender a jornada de construção.

### Código com propósito

O objetivo não é criar código bonito apenas por estética, mas código que explique um conceito e possa ser reutilizado.

### Documentação como parte do laboratório

Cada experimento deve registrar não apenas o “como”, mas também o “por quê”.

### Aprendizado público

Os vídeos e os laboratórios serão usados como uma trilha aberta de estudo e evolução sobre MAF, Foundry e sistemas agentic.

---

## Visão de longo prazo

Este repositório começa como uma coleção de laboratórios, mas a visão é maior.

Com o tempo, ele pode evoluir para uma base de referência sobre:

- Workflows inteligentes em .NET;
- Agentes especializados;
- Integração com Azure AI Foundry;
- Ferramentas conectadas a agentes;
- Processos com aprovação humana;
- Observabilidade de agentes;
- Padrões de automação agentic;
- Fábrica de software com IA;
- Arquiteturas modernas para sistemas inteligentes.

A proposta é construir uma jornada prática, do básico ao avançado, com exemplos reais e explicações acessíveis.

---

## Acompanhe a jornada

Este repositório será atualizado conforme os laboratórios forem sendo gravados, implementados e documentados.

Cada novo laboratório representa uma etapa da jornada de aprendizado.

Se você quer entender como construir aplicações modernas com agentes, workflows e IA aplicada de forma séria, este repositório pode servir como guia prático de estudo.

---

## Status do projeto

Este projeto está em construção contínua.

Novos laboratórios serão adicionados progressivamente, acompanhando os vídeos e os estudos práticos sobre Microsoft Agent Framework, Azure AI Foundry e arquitetura de sistemas agentic.

---

## Contribuições

Contribuições, sugestões e melhorias são bem-vindas.

A ideia é transformar este repositório em uma referência prática para quem deseja aprender e construir soluções com agentes inteligentes usando tecnologias modernas da Microsoft e do ecossistema .NET.

---

## Licença

Este repositório utiliza um modelo de licenciamento duplo:

- O **código-fonte** está licenciado sob a **MIT License**.
- A **documentação, diagramas, vídeos e conteúdos educacionais** estão licenciados sob a **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Ao reutilizar qualquer conteúdo educacional deste repositório, cite a fonte:

**MAF Foundry Labs — Kallebe Lins**

Consulte o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

## Autor

Criado e mantido por Kallebe Lins.

Este repositório faz parte de uma jornada de estudo, prática e construção de soluções modernas com agentes, workflows e inteligência artificial aplicada.