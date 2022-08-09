# Automação de Subsídios

## 1. Ideia Geral

O programa gera um arquivo Word (.docx) formatado e organizado com as informações extraídas de uma planilha de uma determinada UF.

![image](https://user-images.githubusercontent.com/97196457/179800622-5fc2d2fb-b05d-41a5-bbb9-c2b4bb24b4ee.png)

## 2. Contexto e Surgimento da Ideia

Uma das nossas responsabilidades da coordenação/departamento onde trabalho, é a criação de um documento com as informações para subsidiar a viagem da ministra, Cristiane Britto, do Ministério da Mulher, da Família e dos Direitos Humanos. Neste documento deve conter informações sobre as ações a entregas da Secretaria Nacional de Políticas para Mulheres. 

Então tinhamos que filtrar uma planilha por estado e pegar cada informação, copiar, colar no word e formatar. Era algo simples e trabalhoso de ser feito. Neste contexto, a minha coordenadora deu a ideia de automatizar a criação desses documentos. A partir daí corri atrás de uma biblioteca do Python em que pudesse criar documentos ".docx", usei meu conhecimento da biblioteca **Pandas** e corri atrás desse objetivo.

## 3. O que o meu programa faz?
1. Carrega cada aba de uma planilha excel e trata esses dados.
2. Cria um cabeçalho padrão.
3. Cria um título com o nome da UF.
4. Lista todos os convênios da UF.
5. Lista todos os ACTs da UF.
6. Lista todos os TEDs da UF.
7. Lista todos os contratos de repasse da UF.
8. Gera um arquivo .docx.


## Próximos Passos

1. Criar uma interface gráfica para o programa.
2. Tornar a criação online e para qualquer pessoa.


##

<a href="#top">Back to top</a>
