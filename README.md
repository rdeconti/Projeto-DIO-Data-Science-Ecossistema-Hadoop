:spiral_calendar: Atualizado em 25 de junho de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/under_construction.gif" />

:blush: Este projeto está em estudo. Carga inicial realizada para manter cópia de segurança :blush:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One - Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc 
Este projeto foi proposto pela Digital Innovation One
- Link do código original: https://github.com/marcelomarques05/dio-desafio-dataproc
- Professora: Marcelo Marques
- Aula: https://web.digitalinnovation.one/project/criando-um-ecossistema-hadoop-totalmente-gerenciado-com-google-cloud-dataproc/learning/f2a19382-6bbf-4620-a94d-5bb1a46c00c5?back=/track/banco-carrefour-data-engineer

## Descrição
Sua missão será criar um ecossistema de Big Data usando o Google Cloud Platform (GCP). Para isso, o expert te ensinará a configurar o Google Cloud Dataproc, um Hadoop totalmente gerenciado, usando seus créditos gratuitos da GCP.

# Descrição do projeto original
# Digital Innovation One

Código criado para utilização junto a plataforma da Digital Innovation One

<p align="center"><img src="./DIO.png" width="500"></p>

## Desafio GCP Dataproc

O desafio faz parte do curso na plataforma da Digital Innovation One:

__*Criando um ecossitema Hadoop totalmente gerenciado com Google Cloud Platform*__

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contahem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

---

### Etapas do Desafio

1. Criar um bucket no Cloud Storage
1. Atualizar o arquivo ```contador.py``` com o nome do Bucket criado nas linhas que contém ```{SEU_BUCKET}```.
1. Fazer o upload dos arquivos ```contador.py``` e ```livro.txt``` para o bucket criado (instruções abaixo)
    - https://cloud.google.com/storage/docs/uploading-objects

1. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando ```gs://{SEU_BUCKET}/contador.py```
1. O Job irá gerar uma pasta no bucket chamada ```resultado```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

### Entrega do Resultado

1. Criar um repositório no GitHub.
2. Criar um arquivo chamado ```resultado.txt```. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
3. Inserir os arquivo ```resultado.txt``` e ```part-00000``` no repositório e informar na plataforma da Digital Innovation One.

---

### Considerações Finais

NOTA: Se o Job mostrar um WARN de Interrupt, basta ignorar. Existe um bug no Hadoop que é conhecido. Isso não impacta no processamento.

Qualquer outra dúvida, informação ou sugestão, fique a vontade para entrar em contato.

marcelo@smarques.com
