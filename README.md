# Script de Limpeza de Pastas BIN e OBJ

Este script em batch é utilizado para deletar todas as pastas `bin` e `obj` de um projeto, exceto aquelas localizadas dentro da pasta `node_modules`. É uma solução útil para limpar arquivos de build que não são mais necessários.

## Como Funciona

- O script procura, de maneira recursiva, por pastas `bin` e `obj` dentro do diretório atual e seus subdiretórios.
- Pastas dentro de `node_modules` são ignoradas para evitar a exclusão de diretórios importantes para projetos Node.js.
- Após a busca, o script exclui as pastas encontradas de forma silenciosa.

### Pré-requisitos

- Sistema operacional Windows.

### Como Usar

1. Faça o download ou crie um arquivo `.bat` com o conteúdo do script fornecido.
2. Coloque o arquivo no diretório raiz do projeto que você deseja limpar.
3. Dê um duplo clique no arquivo `.bat` para executar o script.

Alternativamente, você pode executar o arquivo via linha de comando:

```bash
Delete-BIN-OBJ.bat
