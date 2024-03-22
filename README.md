# Utilizando AI Search para indexação e consulta de Dados

## Introdução

Neste laboratório será apresentado a utilização de IA para indices de buscas e consulta de dados.

## Início

Primeiro passo foi a criação de um novo recurso: 
    * Azure AI Services - Azure AI Search - criar.
    * Foram preenchidos os dados e finalizado a criação.

![criação recurso](img/capturar1.JPG)

Segundo passo foi a criação de mais um recurso: 
    * Criar recurso - IA + Machine Learning - Serviços Cognitivos - criar.
    * Foram preenchidos os dados e finalizado a criação.

![criação recurso 2](img/capturar2.JPG)

Terceiro passo foi a criação de contas de armazenamento
    * Criar - preencher os dados e finalizar

![criação armazenamento](img/capturar3.JPG)

Após a criação, abri as informações do recurso, acessei as configurações e habilitei a opção *Permitir acesso anônimo ao Blob* e salvei.

![configuração recurso armazenamento](img/captura4.png)

Depois acessei outra opção em Armazenamento de Dados - Contêineres e crie um novo contêiner.

![criação conteiner](img/captura5.png)

Fiz o carregamento dos arquivos .doc do blob.

![carregamento blobs](img/captura6.png)

Depois fiz o acesso ao meu recurso de pesquisa e clico em *importar dados* e inseri as seguinte informações e cliquei em adicionar habilidades...

![config](img/capturar7.JPG)

Em adicionar habilidades, preenchi da seguinte forma:

![habilidades](img/capturar8.JPG)
![habilidades2](img/capturar9.JPG)

Depois cliquei em *Personalizar índice destino*, preenchi as informações e depois cliquei em *criar um indexador*.

![personalizar](img/capturar10.JPG)
![personalizar2](img/capturar11.JPG)

Foi preenchido da seguinte forma e cliquei em enviar.

![indexador](img/capturar12.JPG)

Indexação concluída com sucesso 

![indexador sucesso](img/capturar13.JPG)

Após acessei o Azure AI Search - clico no recurso - gerenciador de pesquisas e fiz uma pesquisa conforme imagem abaixo:

![resultado pesquisa](img/capturar14.JPG)


## Conclusão

Neste laboratório foi possível ter mais conhecimento referente a utilização de IA para indices de buscas e consulta de dados, que é um mecanismo de pesquisa para indexação, pesquisa de texto completo, busca em vetores, pesquisa híbrida e consultas filtradas. 

**OBS: os recursos foram excluídos no final do laboratório**