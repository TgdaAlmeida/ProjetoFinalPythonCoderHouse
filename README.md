 <img style="width:600px" src='logo2.jpeg' alt= 'Logo Coder'>

# Projeto Final 

## Construção de um pipeline de dados utilizando Python.
## Grupo: 
Thiago Gomes de Almeida\
Pedro Alves Junior\
Regiane Alves

## Índice 📖



* <a href='#ferramentas-utilizadas'>Ferramentas utilizadas </a>
* <a href='#bibliotecas-utilizadas'>Importação das biliotecas</a>
* <a href='#conexão-com-o-banco-de-dados-local'>Conexão com o banco de dados local</a>
* <a href='#crianção-de-funções-auxiliares'>Crianção de funções auxiliares</a>
* <a href='#captação-das-urls'>Captação das URLs</a>
* <a href='#criação-dos-dataframes-através-de-apis'>Criação dos DataFrames através de APIs</a>
* <a href='#tratamento-individual-dos-dataframes-gerados'>Tratamento individual dos DataFrames gerados</a>
* <a href='#salvando-e-enviando-os-dataframes-tratados-para-o-banco-de-dados-local'>Salvando e enviando os DataFrames para o banco de dados local</a>

## Ferramentas utilizadas

- Python 3.11.3
- Visual Studio Code

## Bibliotecas utilizadas 

pandas: Usado para trabalhar com dados tabulares, como tabelas, tornando a manipulação de dados estruturados mais conveniente.

datetime: Utilizado para lidar com datas e horas, importante para registros de data e hora ou cálculos temporais.

notification plyer: Possibilita o envio de notificações para a área de trabalho do usuário.

requests: Habilita a realização de solicitações HTTP a servidores web, permitindo a obtenção de dados de recursos online e a interação com APIs web.

sqlite3: Usado para interagir com bancos de dados SQLite, permitindo o armazenamento e recuperação de dados localmente em aplicativos.

json: Facilita a manipulação de dados no formato JSON, comum em comunicações de API e armazenamento de configurações.

## Conexão com o banco de dados local

É aberta uma conexão, através do sqlite3, ao banco de dados local para que os DataFrames resultantes do tratamento pudessem ser armazenados.

## Crianção de funções auxiliares

Foram criadas funções para automatizar o codigo de forma geral, desde a captação das APIs até o envio dos DataFrames gerados para o banco de dandos.

## Captação das URLs

Foram coletadas as URLs alvo e armazenadas em uma variável em formato de lista, para que uma das funções conseguisse percorre-la.

## Criação dos DataFrames através de APIs

Após a captação e teste de conexão automatizado das URLs acima, os DataFrames foram sendo gerados, também automaticamente por uma função, para que possa feitos os tratamentos necessários ao longo do código.


## Tratamento individual dos DataFrames gerados
 
OS três DFs gerados foram tratados individualmente, tendo em vista as necessidades e tipo de daos de cada um.

## Salvando e enviando os DataFrames tratados para o banco de dados local

Após o tratamento individual, foi empregada uma função para enviar esse DataFrame para o banco de dados, acompanhada de outras funções que asseguram a confirmação bem-sucedida do armazenamento e exibição de todos os arquivos salvos no banco de dados, apresentados de maneira tabular.

