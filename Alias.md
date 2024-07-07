# O que é um Alias?

No Linux, um alias é um atalho ou uma forma de criar um comando personalizado que substitui uma sequência de comandos ou um comando longo. Eles são utilizados para simplificar a execução de comandos frequentes, economizando tempo e reduzindo a possibilidade de erros.

## Como Criar um Alias

Você pode criar um alias utilizando o comando `alias` seguido pelo nome do alias e a definição do comando que ele deve substituir. A sintaxe básica é:

```bash
alias nome_alias='comando'
```

Por exemplo, para criar um alias chamado atualizar que execute o comando sudo apt-get update && sudo apt-get upgrade, você pode usar:
```bash
alias atualizar='sudo apt-get update && sudo apt-get upgrade'
```
## Utilizando Aliases
Uma vez que o alias foi criado, você pode usá-lo no terminal como se fosse um comando normal. Por exemplo, usando o alias atualizar criado acima:
```bash
atualizar
```
Isso executará sudo apt-get update && sudo apt-get upgrade.
![image](https://github.com/anadevti/linux-for-beginners/assets/111382055/2155bfcc-30a2-4432-ad2f-d5b86e9270c4)

## Tornando Aliases Permanentes
Os aliases criados desta forma são temporários e só existem na sessão atual do terminal. Para tornar um alias permanente, você deve adicioná-lo ao arquivo de configuração do shell, como .bashrc ou .zshrc, dependendo do shell que você usa.

Abra o arquivo de configuração no seu editor de texto preferido:
```bash
vim ~/.bashrc
```

Adicione o alias ao final do arquivo:
```bash
alias atualizar='sudo apt-get update && sudo apt-get upgrade'
```

Salve o arquivo e recarregue as configurações:
```bash
source ~/.bashrc
```
## Listando Aliases
Para ver uma lista de todos os aliases definidos na sua sessão atual, você pode usar o comando alias sem argumentos:
```bash
alias
```
## Removendo um Alias

Para remover um alias, utilize o comando unalias seguido do nome do alias:
```bash
unalias nome_alias
```

## Conclusão
Aliases são ferramentas poderosas no Linux que ajudam a personalizar e simplificar a utilização do terminal. Com o uso de aliases, você pode criar atalhos para comandos longos ou complexos, melhorando sua eficiência e produtividade no ambiente de linha de comando.
