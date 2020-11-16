# Programação Avançada

Atividade padrão de projeto - **Strategy**.

## Conteúdos

1. [Classificação](https://github.com/igorgodoy/cco-programacao-avancada-strategy#classifica%C3%A7%C3%A3o)
2. [Intenção](https://github.com/igorgodoy/cco-programacao-avancada-strategy#inten%C3%A7%C3%A3o)
3. [Motivação](https://github.com/igorgodoy/cco-programacao-avancada-strategy#motiva%C3%A7%C3%A3o)
4. [Aplicação](https://github.com/igorgodoy/cco-programacao-avancada-strategy#aplica%C3%A7%C3%A3o)
5. [Estrutura](https://github.com/igorgodoy/cco-programacao-avancada-strategy#estrutura)
6. [Participantes](https://github.com/igorgodoy/cco-programacao-avancada-strategy#participantes)
7. [Implementação](https://github.com/igorgodoy/cco-programacao-avancada-strategy#implementa%C3%A7%C3%A3o)

## Strategy

### Classificação

- O **Strategy** é um padrão de projeto que define comportamentos de uma objeto assumindo para eles um contexto. Desta forma é possível que este objeto e suas diversas funções sejam separadas em classes, as quais podem ser acionadas de acordo com o contexto definido.

### Intenção

- Tornar o código menos verboso, abstraindo métodos em diversas classes variadas por um contexto.

### Motivação

- Tornar o código mais legível, facilitar manutenção e novas implementações.

### Aplicação

- Comumente utilizados em métodos de pagamento, upload e storage de arquivos, interfaces, etc.

### Estrutura

- Este [diagrama](https://refactoring.guru/images/patterns/diagrams/strategy/structure-2x.png) representa uma estrutura elaborada baseada nos padrões do **Strategy**.

### Participantes

- *Context*: define a referência para uma das classes strategyclasse strategy específica;
- *Strategy*: interface comum entre todos os algoritmos suportados;
- *ConcreteStrategy*: algoritmo(s) fornecido(s) para a aplicação.

### Implementação

[Implementação](https://github.com/igorgodoy/cco-programacao-avancada-strategy/tree/main/example) onde o padrão Strategy foi utilizado para definir um dos métodos de pagamento implementados de um e-commerce a ser utilizado e escolhido pelo cliente.
