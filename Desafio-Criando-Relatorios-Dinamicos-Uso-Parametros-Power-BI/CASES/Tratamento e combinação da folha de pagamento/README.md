# ETL da folha de pagamento e modelo de dados
Um grupo empresarial exporta mensalmente um relatório da folha de pagamento do seu sistema de gestão.  O arquivo é exportando na extensão `.xlsx`, possui uma empresa por arquivo e um período de competência. No cabeçalho do arquivo é mostrado a competência no qual o relatório faz referência.

Veja o exemplo a seguir:

![image](https://user-images.githubusercontent.com/24781333/220169817-29ed3206-cf8e-4d54-be82-576f2fd4feae.png)

No exemplo, as premissas do arquivo são:
* A competência é _01/10/2019_, com isso a data que abrange este arquivo é entre a data _01/10/2019 a 31/10/2019_;
* A empresa no qual o relatório faz referência é o _GRUPO ADRAUDE VAREJISTA_, com o CNJP _032.622.214/0001-20_

O sistema de gestão não possui um relatório de forma tabular para que os usuários possam usar estes dados com o objetivo de criar relatórios gerenciais que não existem no sistema. Com isso, o analista do departamento pessoal, mensalmente, exporta um relatório de cada empresa e, manualmente, copia e cola os dados de forma tabular, deixando algo parecido com a imagem abaixo:
![image](https://user-images.githubusercontent.com/24781333/220171290-58296af8-0914-420f-bb8e-b316d6dd80d7.png)


## OBJETIVO

**1.** Usando o Power Query, tratar os dados do diretório `baseFolha` e transformá-lo em uma versão tabular;
_**1.1.** Será salvo, mensalmente, os arquivos do período por empresa em um diretório;_
_**1.2.** O Power Query, irá consolidar todos os arquivos que estiverem dentro deste diretório, no qual irá conter todos os meses de cada empresa;_

**2.** Criar um modelo de dados para ser usado nos relatórios;

**3.** Criar um relatório resumindo informações com base no modelo de dados.

> **Obs. 1:** As regras de como proceder na entrega do resultado desenvolvido, está na raiz deste repositório: [TestePowerBI (github.com)](https://github.com/pietrofarias/TestePowerBI).  Acesse [Premissas para o DESENVOLVEDOR](https://github.com/pietrofarias/TestePowerBI#premissas-para-o-desenvolvedor-avaliado) para saber mais;

> **Obs. 2:** Deve ser criado um parâmetro para poder identificar qual o endereço do diretório no computador do avaliador. Acesse [Requisitos para o envio do teste](https://github.com/pietrofarias/TestePowerBI#requisitos-para-o-envio-do-teste) para saber mais;

## Modelo de Dados (Conjunto de dados / _Dataset_) esperado
Espera-se que o modelo de dados tenha uma configuração mínima, mas não limitando-se a isso, como no exemplo abaixo:
![image](https://user-images.githubusercontent.com/24781333/220172381-b91e4c67-7636-4e8e-861d-e5f6ffe2ae74.png)

As configurações de cada campo das tabelas, estão nas próximas imagens:
#### `dEmpresa`
![image](https://user-images.githubusercontent.com/24781333/220172714-424e98c5-1f13-4c3d-a25e-e61b4df67c02.png)

----
#### `dLancamento`
![image](https://user-images.githubusercontent.com/24781333/220172847-b59c48ab-8781-4432-9b81-fa4a5844eb08.png)

---
#### `dFuncionario`
![image](https://user-images.githubusercontent.com/24781333/220172923-ec3990fe-1bf0-4437-a104-6b826e9d6e3f.png)

---
#### `dLoja`
![image](https://user-images.githubusercontent.com/24781333/220173164-cb2207dc-ee3e-4e9c-98e3-0877e22f20d9.png)

---
####  `fFolhaPagamento`
![image](https://user-images.githubusercontent.com/24781333/220173261-93e222ed-7156-42f8-ae56-a7dbc7c94266.png)

---

## O que será avaliado?
* Uso do Power Query para tratamento básico e combinação de dados;
* Criar estrutura de um modelo de dados com combinação de arquivos;
* Entendimento no desenvolvimento de relatórios;

## O que não será avaliado?
* O design do relatório. O mais importante é o que o relatório apresenta e a experiência do usuário referente aos filtros;
