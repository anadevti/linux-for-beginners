# Guia Básico de Ubuntu para Iniciantes

Este guia em formato Markdown oferece uma introdução básica para novos usuários do Ubuntu, cobrindo desde a instalação até a gestão básica do sistema e a instalação de aplicativos.

## Introdução ao Ubuntu

Ubuntu é uma das distribuições Linux mais populares, desenvolvida pela Canonical Ltd. É conhecido por sua facilidade de uso e excelente suporte comunitário.

## Instalação do Ubuntu

Antes de instalar, você pode experimentar o Ubuntu sem alterar o seu sistema usando a opção "Try Ubuntu" do instalador. Para instalar:

1. **Baixe a ISO** do Ubuntu: [Download Ubuntu](https://ubuntu.com/download)
2. **Crie um pendrive bootável** ou grave em um DVD.
3. **Reinicie o computador** e inicie a partir do pendrive/DVD.
4. Siga as **instruções na tela** para completar a instalação.

## Configurando o Sistema

Após a instalação, você pode querer configurar algumas coisas:

- **Atualizações de Software**: Vá até "Software & Updates" para configurar atualizações automáticas.
- **Instalação de Drivers**: Drivers adicionais podem ser necessários para hardware específico, acessíveis via "Software & Updates" na aba "Additional Drivers".

## Comandos Básicos do Terminal

O terminal é uma parte essencial da experiência Linux. Aqui estão alguns comandos básicos:

- `sudo apt update`: Atualiza a lista de pacotes disponíveis.
- `sudo apt upgrade`: Atualiza todos os pacotes instalados para a versão mais recente.
- `ls`: Lista os arquivos em um diretório.
- `cd <diretório>`: Muda para outro diretório.
- `mkdir <nome>`: Cria um novo diretório.
- `rm <arquivo>`: Remove um arquivo.

## Instalando Aplicativos

Ubuntu utiliza o gerenciador de pacotes APT. Para instalar um novo aplicativo:

```bash
sudo apt install <nome_do_pacote>
