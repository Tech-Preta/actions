# actions

Repositório [`Tech-Preta/actions`](https://github.com/Tech-Preta/actions).

Este arquivo descreve somente o que está versionado no repositório. Onde o código não define um comportamento, a seção fica marcada como **pendente**.

## Propósito

**Pendente.** Nenhum arquivo do repositório declara o propósito do projeto.

O conteúdo versionado antes desta documentação era apenas o título `# actions` neste `README.md`. O nome do repositório é `actions`. Não há, no código, uma definição do que esse nome deve significar na prática.

## Estrutura do repositório

A árvore versionada contém um único arquivo:

```text
.
└── README.md
```

O repositório não inclui, em nenhum caminho:

- `action.yml` ou `action.yaml`
- diretório `.github/workflows/`
- workflow reutilizável (`workflow_call`)
- script de shell, JavaScript, Python ou outra linguagem
- `Dockerfile`
- testes
- `LICENSE`
- `CONTRIBUTING.md`
- código de conduta
- modelos de issue ou de pull request
- `CODEOWNERS`

## Pré-requisitos

**Pendente.** Nenhum arquivo lista runtime, versão de ferramenta, action de Marketplace ou outro pré-requisito.

## Como usar

**Pendente.** Não há action composta, action em JavaScript ou Docker, nem workflow reutilizável para referenciar com `uses:`.

Também não há inputs nem outputs definidos. Este README não traz exemplo de uso porque não existe um contrato em `action.yml` nem em `on.workflow_call` para reproduzir.

Quando esse contrato existir no código, o exemplo desta seção deve usar apenas os nomes de inputs e outputs declarados ali.

## Configuração

**Pendente.** O código não declara configuração consumida por uma action ou por um workflow.

| Item | O que o código contém |
| --- | --- |
| Inputs | Nada. Não há `action.yml` nem `on.workflow_call.inputs`. |
| Outputs | Nada. Não há `action.yml` nem `on.workflow_call.outputs`. |
| Segredos | Nenhum nome. Não há chave `secrets:` nem expressão `secrets.*`. |
| Permissões | Nenhuma. Não há chave `permissions:` em workflow. |

Não há valores de segredo versionados. Também não há lista de segredos que alguém deva configurar: nenhum arquivo cita um nome de segredo.

## Como contribuir

**Pendente** o guia formal de contribuição. O repositório não versiona `CONTRIBUTING.md`, código de conduta, licença, `CODEOWNERS` nem modelos de issue e pull request, então não há processo de revisão nem termos de uso definidos em arquivo.

Mudanças entram pelo fluxo padrão de pull request do GitHub neste repositório. Se um pull request adicionar action ou workflow, a definição (`action.yml` ou workflow) precisa vir no próprio código, e este README só deve passar a citar inputs, outputs, segredos e permissões que esses arquivos declararem.
