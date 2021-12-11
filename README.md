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

# **Perguntas respondidas neste repositorio**

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
> Para Age, a abordagem foi separar a média de idade por Sexo e Classe, imaginando uma situação de que por classe teriamos uma proximidade de idades de acordo com classe social da época e por homen e mulher da mesma madeira.

![image](https://user-images.githubusercontent.com/95967979/145682312-6a6bb6fe-7baa-4d4b-9b0e-5e65732f6aa7.png)


> Para Embarked, adotei o porto de embarque que tem maior numero de embarques para preencher os 2 dados faltantes.

![image](https://user-images.githubusercontent.com/95967979/145682327-37efc046-821f-411c-8266-f3a94345eaee.png)


> Para Cabin, aloquei os 77,1% dos dados faltantes em um status de Deck.

São 577 Homens e 314 Mulheres à bordo

![image](https://user-images.githubusercontent.com/95967979/145682363-c9cd0490-01c1-47fd-b030-97271baaed9a.png)

São 549 não sobreviventes e 342 sobreviventes

![image](https://user-images.githubusercontent.com/95967979/145682409-540ee9bb-0b50-434a-913f-93e9146ef17e.png)

No total 81 mulheres não sobreviveram

![image](https://user-images.githubusercontent.com/95967979/145682434-cea293bb-90e5-4e6a-8d8d-aed420c3704d.png)

Proporção base o total de passageiros que não sobreviveu e sobreviveu por sexo

![image](https://user-images.githubusercontent.com/95967979/145682452-7188ecbc-002a-4d5b-ac59-25e9667788c1.png)



# **Contribuições e pesquisas**

http://titanicemfoco.blogspot.com/2011/10/dentro-do-titanic-uma-visao-geral.html
