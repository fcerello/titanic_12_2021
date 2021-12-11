# CONTRIBUIÇÕES PARA DATASET DO TITANIC
![image](https://user-images.githubusercontent.com/95967979/145679664-9df8157d-9b92-44c4-9a32-9b8ece15f7e8.png)
> **Nota:** imagem de internet, apenas para ilustração.
 
# **Contexto do Repositorio**

Contribuir para os diversoes estudos didaticos e aprendizados de Ciências de dados, Estatísticas e Machine Learning


# **O que temos de dados nas 12 colunas**
|                |Nota                         |Dado                        |
|----------------|-------------------------------|-----------------------------|
|PassangerId|`Identificador do passageiro`            |-            |
|Survived          |`Sobreviveu?`            |0 == Não, 1 == Sim            |
|Pclass          |`Classe de ingresso`|1 == 1a classe , 2 == 2a classe, 3 == 3a classe|
|Name         |`Nome do passageiro`|Sobrenome, Titulo. Nome (compania de viagem)|
|Sex          |`Sexo do passageiro`|male == masculino, female == feminino|
|Age          |`Idade em anos`|-|
|Sibsp          |`Quantidade de irmãos / cônjuges a bordo do Titanic`|-|
|Parch          |`Quantidade de pais / crianças a bordo do Titanic`|-|
|Ticket          |` Número do bilhete de embarque`|-|
|Fare          |`Tarifa paga pelo Passageiro`|-|
|Cabin          |`Número de cabine`|-|
|Embarked          |`Porto de Embarque`|C = Cherbourg, Q = Queenstown, S = Southampton|
dataset > titanic.data


# **Tipo de dados originais do dataset:**
|                |Tipo                         |
|----------------|-------------------------------|
|PassangerId|`int64`            |
|Survived          |`int64`            |
|Pclass          |`int64`|
|Name          |`object`|
|Sex          |`object`|
|Age          |`float64`|
|Sibsp          |`int64`|
|Parch          |`int64`|
|Ticket          |` object`|
|Fare          |`float64`|
|Cabin          |`object`|
|Embarked          |`object`|


# **Dataset possui 891 linhas de dados e dados faltantes em:**

Age: 19.9% de dados faltantes

Cabin: 77,1% de dados faltantes

Embarked: 0,2% de dados faltantes

# **Perguntas respondidas nes repositorio**

- Quantas linhas e colunas tem o dataset? Quais os tipos das colunas?
- Quantos dados faltantes o dataset possui?
- Quantas mulheres e quantos homes estavam à bordo?
- Quantos passagueiros sobreviveram e quantos não sobreviveram?
- Quantas mulheres não sobreviveram?
- Proporcionalmente, sobreviveram mais homens ou mais mulheres?
- Levando-se em consideração a idade dos passageiros, qual a idade e quantidade de pessoas com maoir número de mortos?
- Qual a média de idade dos homens sobreviventes?
- Levando-se em consideração passageiros prioritários, qual a proporção de sobreviventes por sexo? (mulher e crianças de até 15 anos independente do sexo)
- Qual a quantidade de passagueiros por classe?
- Qual o percentual de sobreviventes por classe?
- A quantidade de sobreviventes e não sobreviventes, agrupados por sexo e classe
- Dos homens com idade entre 24 e 30 anos quantos da classe 3 sobreviveram? Quantos da classe 2 não sobreviveram?
- POdemos afirmar que mulheres sobreviventes são mais numeroras que os homens? em qual classe e qual faixa de idade?

# **Algumas das respostas para os questionamentos**

Quantidade de dados faltantes, Age 19,9%, Cabin 77,1% e Embarked 0,2%
![image](https://user-images.githubusercontent.com/95967979/145681962-74e6108e-700c-4cba-82ec-4f991de6e07a.png)
![image](https://user-images.githubusercontent.com/95967979/145681964-c75302db-b8e0-415c-90ad-426b825863be.png)

> Para preencher os dados faltantes, adotei o vies de que não podemos perder nenhuma linha de dados e para cada coluna temos um modo de preencher


# **Contribuições e pesquisas**

http://titanicemfoco.blogspot.com/2011/10/dentro-do-titanic-uma-visao-geral.html
