# Documentação do Projeto Hermes

## Índice

1. Introdução
2. Bibliotecas Utilizadas
3. Configuração do Ambiente
4. Execução do Projeto

## Introdução

Reinventando a maneira como absorvemos informações, Hermes surge como o deus dos atalhos no mundo digital. Ele oferece uma solução inovadora para simplificar a complexidade do conteúdo textual, com a capacidade de resumir documentos nos formatos DOC, PDF e TXT. O Hermes é construído com Python e integrado com a API da OpenAI.

## Bibliotecas Utilizadas

- **openai**: Utilizada para acessar a API da OpenAI.
- **python-dotenv**: Utilizada para gerenciar variáveis de ambiente.
- **python-docx**: Utilizada para criar, modificar e extrair informações de documentos .docx.
- **PyPDF2**: Utilizada para manipular arquivos PDF.

## Configuração do Ambiente

1. Baixe o VSCode
2. Baixe o Python
3. Crie uma conta na OpenAI e gere sua chave API

Instale as bibliotecas necessárias com os seguintes comandos:

pip install openai
pip install python-dotenv
pip install python-docx
pip install PyPDF2

## Execução do Projeto

Para executar o projeto Hermes, siga os passos abaixo:

1. Vá até a pasta do programa.
2. Crie uma subpasta chamada '0_Texto' e coloque os textos que deseja resumir dentro dela.
3. Execute o programa via VSCode.
4. Você será solicitado a selecionar o arquivo que deseja resumir.
5. Após a execução, uma pasta chamada '1_Resumo' será criada. Esta pasta conterá os resumos gerados.

Por favor, note que você deve ter todas as bibliotecas necessárias instaladas e a chave API da OpenAI configurada corretamente para que o programa funcione.