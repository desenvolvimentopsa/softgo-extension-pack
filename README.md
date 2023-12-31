# Softgo Extension Pack
Desenvolvedores na SoftGO - Conjunto de Extensões para VsCode.

## Extensões

- [EditorConfig for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Esse plugin sobreescreve as configurações do editor baseado no arquivo `.editorconfig` local.

- [VS Code ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integra o Eslint no editor para buscar erros.

- [Prettier Formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Um plugin que roda o prettier para formatar arquivos.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automaticamente renomeia a tag par que está sendo modificada.

- [vscode-duplicate](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-duplicate) - Facilita para duplicar arquivos e também diretórios inteiros.

- [VSCode Advanced New File](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file) - Permite criar arquivos e pastas de forma mais prática.

- [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame) - Mostra na barra de status o commit que modificou a linha selecionada.

- [Microsoft Visual Studio Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) - Permite compartilhar o editor para fazer pair-programming.

- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components) - Syntax highlighting para Styled Components.

- [VS Code JavaScript (ES6) snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) - Alguns snippets úteis para JavaScript.

- [vscode-jest-snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets) - Alguns snippets úteis para Jest (framework de testes).

- [JS JSX Snippets](https://marketplace.visualstudio.com/items?itemName=skyran.js-jsx-snippets) - Alguns snippets úteis para React e JSX em si.

- [Snippets úteis para NextJS](https://marketplace.visualstudio.com/items?itemName=PulkitGangwar.nextjs-snippets) - Alguns snippets úteis para NextJS.

- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) - Tema Dark utilizado no VScode.

- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next) - Habilita o suporte JavaScript e TypeScript para as próximas versões.

- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - Fornece recursos de desenvolvimento assistido por IA, baseados no contexto do código combinado com machine learning.


## Como desenvolver e instalar localmente

- Clone o repositório

```bash
$ git clone https://github.com/desenvolvimentopsa/softgo-extension-pack
```

- Instale o vsce

```bash
$ npm install -g vsce
```

- Crie o pacote da extensão

```bash
$ vsce package
```

- Instale a extensão através do arquivo `.vsix`

1. Abra o VS Code
2. Selecione **Extensions** do menu
3. Clique em **More** > **Install from VSIX...**
4. Selecione o arquivo `softgo-extension-pack-x.x.x.vsix`
5. Clique em **Reload Now** para recarregar o VS Code

## Este é um README.md derivado/alterado do curso React Avançado do Willian Justen
