# Plano Brasil Possível

Projeto de longo prazo para investigar, de forma incremental, que problemas o Brasil tem, por que eles existem, quem é afetado e quais políticas apresentam melhores resultados diante de objetivos sociais explícitos.

O plano não nasce comprometido com esquerda, direita ou centro. Também não trata todo argumento como igualmente válido. Quando a evidência apontar com clareza para uma conclusão, o projeto deve registrá-la, qualquer que seja o campo que costume defendê-la.

A premissa de partida é outra: pessoas de orientações diferentes podem concordar que o país poderia ser melhor e, a partir daí, examinar cada problema separadamente — motivações, interesses, custos, benefícios e consequências.

## O que este repositório é

Um sistema de investigação em Markdown, com histórico preservado. O sucesso pretendido não é o volume de propostas, e sim a qualidade do raciocínio, a consistência do método, a transparência das evidências e a capacidade de mudar de posição quando a evidência o exigir.

Nada aqui é ainda um plano de governo fechado. A etapa atual é a classificação socioeconômica.

## Motivação

A polarização dificulta o debate: propostas passam a ser aceitas ou rejeitadas pela identificação de quem as defende, antes do exame do conteúdo. Este projeto tenta inverter essa ordem. Para cada política, deve ser possível responder:

- Qual problema se quer resolver, e por que ele existe.
- Quem é afetado e quais interesses econômicos estão envolvidos.
- Quais soluções existem.
- Quanto custam, quem financia, quais benefícios e quais danos.
- Como o resultado será avaliado.

## Método

As afirmações do projeto são classificadas como fato, hipótese, valor, interpretação, proposta, decisão ou questão aberta. Hipótese registrada continua hipótese.

Estado e mercado são instrumentos a comparar por setor, não pontos de partida morais. Responsabilidade fiscal e responsabilidade social são examinadas juntas.

Detalhes: [`fundamentos/principios.md`](fundamentos/principios.md) e [`fundamentos/metodologia.md`](fundamentos/metodologia.md).

## Estágio atual

**Fase 1 — Classificação socioeconômica.** Status: em discussão.

Existe uma classificação provisória de nove classes. Faixas de renda, nomes e critérios de enquadramento não estão consolidados. A próxima pergunta é qual critério prevalece quando renda, patrimônio e dependência do trabalho divergem.

Ponto de entrada para continuar o trabalho: [`CONTEXTO.md`](CONTEXTO.md).

## Como navegar

| Quero… | Ir para |
|---|---|
| Retomar o trabalho | [`CONTEXTO.md`](CONTEXTO.md) |
| Ver as etapas | [`ROADMAP.md`](ROADMAP.md) |
| Entender as regras do projeto | [`fundamentos/principios.md`](fundamentos/principios.md) |
| Ver as nove classes | [`fundamentos/classificacao-socioeconomica.md`](fundamentos/classificacao-socioeconomica.md) |
| Ver o que ainda não foi decidido | [`fundamentos/questoes-em-aberto.md`](fundamentos/questoes-em-aberto.md) |
| Ler as formulações de origem | [`arquivo/contexto-original.md`](arquivo/contexto-original.md) |
| Orientar um agente novo | [`AGENTS.md`](AGENTS.md) |
| Ver o histórico de mudanças | [`CHANGELOG.md`](CHANGELOG.md) |

## Estrutura

```
fundamentos/     princípios, método, classes, critérios, hipóteses, questões
diagnostico/     panorama do país (ainda não pesquisado)
propostas/       pautas setoriais (ainda não abertas)
evidencias/      fontes, estudos e dados
contrapontos/    objeções e divergências de método
decisoes/        decisões explícitas, no formato de registro
discussoes/      fila de discussão e histórico
templates/       modelos de proposta, evidência, decisão e impacto
arquivo/         formulações originais, preservadas
```

Arquivos de etapas futuras declaram apenas finalidade e status. Eles não contêm diagnóstico nem proposta inventados para ocupar espaço.

## Versionamento

O rastreio das mudanças será feito com Git. Commits, pushes e publicação externa dependem de autorização. Mensagens sugeridas para mudanças conceituais estão em [`AGENTS.md`](AGENTS.md) e no [`ROADMAP.md`](ROADMAP.md).

Um commit inicial ainda não foi feito. Mensagem sugerida, quando autorizado: `docs: estrutura inicial do projeto`.
