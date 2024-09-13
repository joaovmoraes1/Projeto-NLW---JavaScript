# Aplicativo de Metas em Node.js

Este projeto é um aplicativo de gestão de metas simples implementado em Node.js, utilizando a biblioteca Inquirer para interação com o usuário. O aplicativo permite que você crie, gerencie e acompanhe suas metas de forma eficiente.

## Funcionalidades Principais

- Cadastrar meta: Adicionar novas metas à lista
- Listar metas: Exibir todas as metas cadastradas, com opção de filtrar por metas realizadas ou abertas
- Marcar/Desmarcar metas como concluídas: Permite marcar metas como concluídas e desmarcá-las posteriormente
- Remover metas: Eliminar metas da lista
- Sistema de mensagens: Exibir mensagens informativas durante a execução do aplicativo
- Persistência de dados: As metas são armazenadas em um arquivo JSON para preservação entre sessões

## Como Usar

### Instalação

```bash
npm install
```

### Execução

```bash
node index.js
```

### Interação

O aplicativo apresentará um menu com as opções disponíveis. Use as teclas de seta para navegar pelas opções e pressione Enter para selecionar.

## Estrutura do Código

O código está organizado em módulos responsáveis:

- `index.js`: Arquivo principal com o loop principal do aplicativo e lógica de navegação
- `metas.json`: Arquivo onde as metas são armazenadas

## Dependências

- Inquirer: Biblioteca para criar prompts interativos no terminal
- fs: Módulo nativo do Node.js para manipulação de arquivos

## Considerações Adicionais

Este é um exemplo simples que pode ser expandido com funcionalidades adicionais, como:

- Adicionar datas de vencimento para as metas
- Implementar notificações para metas próximas
- Criar diferentes categorias para as metas

O código também pode ser refatorado para melhorar a organização e modularidade.

## Próximos Passos

1. Implementar novas funcionalidades
2. Refatorar o código para otimizar estrutura e organização
3. Criar testes para garantir qualidade do código

## Conclusão

Este projeto serve como ponto de partida para um aplicativo de gestão de metas mais completo. Explore as funcionalidades, o código e as considerações apresentadas para aprimorar o aplicativo conforme necessário.
