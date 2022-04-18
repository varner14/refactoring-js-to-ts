Como esse é um projeto CRA sem TypeScript, você primeiro precisar instalar as dependências/tipagens e configurar o TS. Nossa sugestão é criar um novo projeto CRA com Typescript e comparar a estrutura atual com a que você precisa ter. Realizando essa comparação, facilmente você consegue ver que:

- É preciso instalar o `typescript`
- É preciso criar um arquivo de configuração `tsconfig.json`. Inclusive, você pode utilizar a configuração gerada automaticamente no CRA template Typescript para criar o seu arquivo.
- É preciso criar um arquivo `react-app-env.d.ts` com o conteúdo:

- É preciso instalar as tipagens das bibliotecas.

Configurando esse setup, você deve ser capaz de trabalhar normalmente com o Typescript no seu projeto.

## Estou com dificuldade na conversão classes→função

Caso você tenha dificuldade nesse processo de migração, dê uma olhada no nosso guia sobre esse assunto:

[Componentes no React](https://www.notion.so/Componentes-no-React-6644d41da663405cb29dcaae1693bb9f)