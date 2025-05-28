# Teste Técnico Amicci

## Contexto do Problema

A Amicci é uma companhia que conecta indústrias à varejistas para criação de projetos de desenvolvimento de produtos de marca-própria. Para que esse processo ocorra, é necessário um sistema para gerenciamento de projetos. 

No modelo de negócio da Amicci, em um mesmo projeto, indústria e varejista podem negociar, desenvolver e produzir N produtos, também chamados de SKUs.

Os SKUs podem ter diversas categorias: alimentos, pet, mercearia seca, etc.

As etapas padrão dos projetos de marca própria são:
1. Especificação do(s) produto(s) desejados para fabricação no projeto
   - Responsável: varejista
2. Seleção da indústria que realizará o projeto e fabricação dos produtos.
   - Responsável: varejista
3. Formalização dos acordos feitos entre varejo e indústria após negociação de valores e quantidades.
   - Responsáveis: indústria e varejista
4. Desenvolvimento do(s) produto(s)
   - Definição de identidade da marca, design, dados regulatórios e impressão
   - Responsáveis: indústria e varejista
5. Produção
   - Fabricação e entrega do produto para o varejista
   - Responsável: indústria

## Estrutura do Repositório Base

O candidato receberá:

1. **Documentação**
    - Descrição do problema de negócio
    - Requisitos técnicos
    - Critérios de avaliação
    - Especificação da API (arquivo YAML)
2. **Dados de Exemplo**
    - Arquivo JSON com dados de exemplo para importação

## Requisitos Técnicos

### Back-end

- Django ou Fast-API
- PostgreSQL

### Front-end

- React 18+
- TypeScript
- SCSS para estilização

### Pontos adicionais de Back e Front (Opcionais)

- Next
- Docker e docker-compose
- Testes unitários

## Histórias de Usuário

### História 1: Criação e Edição de Projetos

**Como** varejista

**Quero** criar e editar projetos

**Para** gerenciar informações de projetos

**Critérios de Aceitação:**

- Formulário com validação de campos
- Seleção de fornecedor e categoria
- Feedback visual de sucesso/erro
- Garantir que a interface seja responsiva

### História 2: Listagem e Filtro de Projetos

**Como** varejista

**Quero** visualizar e filtrar meus projetos na plataforma

**Para** acompanhamento das informações e status dos projetos

**Critérios de Aceitação:**

- Exibir lista de projetos com informações principais (nome, varejista, responsável, categoria)
- Permitir filtrar por categoria e indústria
- Implementar paginação para resultados
- Garantir que a interface seja responsiva

## Tarefas do Candidato

### Back-end

1. **Configuração do Projeto**
    - Criar e configurar um novo projeto
    - Configurar Docker e docker-compose (opcional)
    - Implementar sistema de autenticação (JWT)
2. **Modelagem de Dados**
    - Implementar os modelos necessários baseados na especificação
    - Criar relacionamentos apropriados entre entidades
    - Implementar validações de negócio
3. **Implementação da API**
    - Desenvolver endpoints para gerenciamento de briefings
    - Implementar filtros e ordenação
    - Garantir segurança e validação de dados
4. **Testes**
    - Implementar testes unitários e de integração

### Front-end (React/TypeScript)

1. **Configuração do Projeto**
    - Criar e configurar um projeto React com TypeScript
    - Configurar sistema de estilização com SCSS
    - Implementar estrutura de roteamento
2. **Arquitetura de Estado**
    - Implementar gerenciamento de estado (Context API, Redux ou similar)
    - Configurar integração com a API do back-end
3. **Componentes e UI**
    - Desenvolver componentes para listagem e formulário de briefings
    - Implementar filtros e pesquisa
    - Garantir responsividade e acessibilidade básica
4. **Testes**
    - Implementar testes unitários para componentes

## Desafios Técnicos Adicionais (Opcionais)

Para candidatos que concluírem as tarefas básicas e desejarem demonstrar habilidades avançadas:

1. **Back-end**
    - Implementar cache para otimizar consultas frequentes
    - Implementar política de rate-limit
    - Criar um endpoint para relatórios agregados simples
    - Implementar versionamento da API
2. **Front-end**
    - Lazy Loading e Divisão de Código
    - Renderização de Listas com Virtualização
    - Renovação Automática de Tokens
    - Cobertura de Testes Automatizados (mínimo de 80%)
    - Criar componente de visualização de dados (gráfico ou tabela dinâmica)
    - Implementar tratamento avançado de erros e retry de requisições

## Critérios de Avaliação

### Arquitetura e Design

- Organização do código e separação de responsabilidades
- Padrões de projeto e boas práticas
- Decisões técnicas e trade-offs (documentados)
- Diagrama da Arquitetura do Sistema

### Qualidade de Código

- Legibilidade e manutenibilidade
- Testes automatizados
- Tratamento de erros e edge cases

### Funcionalidade

- Implementação completa dos requisitos
- Performance e otimizações
- Experiência do usuário

### Habilidades Técnicas

- Domínio das tecnologias
- Implementação de autenticação e segurança
- Uso avançado de recursos das frameworks

## Instruções para o Candidato

1. Implemente o back-end e front-end conforme especificado
2. Documente decisões técnicas e arquiteturais
3. Inclua instruções claras para execução do projeto
4. Envie o link do seu repositório até o prazo estipulado
