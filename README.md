# Projeto React básico com Vite

## Criação do projeto

1. Criação do projeto: `npm create vite@latest`;
1. Responder as perguntas do `create vite`;
1. Entrar na pasta do projeto: `cd nome-do-projeto`;
1. Abrir no VSCode: `code .`;
1. Instalar os pacotes: `npm install`;
1. Rodar o projeto: `npm run dev`;
1. Abrir o navegador: `http://localhost:5173`;

## Alteração do projeto

1. Remover o arquivo `src/App.css`;
1. Remover o arquivo `src/index.css`;
1. Alterar o arquivo `src/App.jsx`:
    - remover os imports;
    - apagar o retorno da função;
    - adicionar novo retorno da função:
        ```jsx
        return (
            <>
                <h1>Hello World</h1>
                <div>
                    <h2>Nova página sem css</h2>
                </div>
                <p>
                    Este é um paragrafo de teste.
                </p>
            </>
        )
        ```

*Observação*: Você pode inserir o conteúdo da sua página entre as tags `<>` e `</>`.