# Introdução ao GitHub Actions

## Contexto
O GitHub Actions é uma ferramenta poderosa para automação, CI/CD e outras operações de pipeline. Esta atividade prática visa introduzir a equipe ao GitHub Actions e criar um entendimento prático de como configurar workflows, jobs e steps, além de entender como os runners do GitHub Actions operam.

## Objetivo
Configurar um workflow básico no GitHub e executar uma série de jobs simples para entender como o GitHub Actions funciona.

---

# Passo 1 - Acesso ao Repositório

## Acessem seu repositório no GitHub.
Naveguem até o repositório desejado para configurar o GitHub Actions.

---

# Passo 2 - Criação de um Novo Workflow

## Criem um novo workflow.
Na página do repositório, cliquem em "Actions" e selecionem "set up a workflow yourself" para criar um novo arquivo de workflow.

---

# Passo 3 - Configuração do Workflow

## Configurem o arquivo de workflow.
Adicionem os jobs necessários e façam um push para o repositório.
Observem o workflow em ação.

---

# Exemplo de Configuração do Workflow

## Nome dos Jobs, Eventos e Descrições

- **Job 1: Testes Automatizados**
  - **Evento:** Disparado por push
  - **Descrição:** Realiza testes automatizados para garantir a integridade do código.

- **Job 2: Implantação no Ambiente de Produção**
  - **Evento:** Disparado por pull request
  - **Descrição:** Implanta o código no ambiente de produção após a revisão de um pull request.
