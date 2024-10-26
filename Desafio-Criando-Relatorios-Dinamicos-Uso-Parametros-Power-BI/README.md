Ivan Wagner

# Teste de nivelamento Power BI

O principal objetivo deste repositório é facilitar a avaliação técnica dos desenvolvedores. No repositório contém alguns _cases_ no qual serão usados para testar estes conhecimentos referente a alguma parte das soluções do Power BI, seja o _Power BI Serviços_ ou _Power BI Desktop_.

Para que a avaliação seja justa tanto para o Avaliador como para o Desenvolvedor Avaliado, será necessário seguir algumas regras apresentadas neste documento.

> **Atenção:** O uso dos arquivos, fonte de dados ou qualquer outro item deste repositório, deverá seguir estas regras. Caso contrário, irá infringir os termos de uso.    
  
#### ÍNDICE
| Seção | Sobre o que trata? |
|--|--|
|[Premissas para o avaliador](#premissas-para-os-avaliadore) |Como os avaliadores devem usar este repositório|
|[Premissas para o desenvolvedor avaliado](#premissas-para-o-desenvolvedor-avaliado) | Como funcionará a avaliação
|[Requisitos para o envio do teste](#requisitos-para-o-envio-do-teste) | Regras para o envio do teste para o avaliador




# Premissas para os AVALIADORES
* Entendemos que as vezes existe a necessidade de entender com maior precisão todos os conhecimentos técnicos do desenvolvedor. Mas use o bom senso da quantidade de _cases_ que deverão ser aplicados, por entender que cada _case_ pode possuir uma complexidade no qual usará muito tempo do desenvolvedor;

*  **SEMPRE FAÇA UM FEEDBACK**. Muitos desenvolvedores esperam entender onde podem melhorar e se preparar para um outro momento. Então informe quais foram os pontos que fizeram escolher a não seguir com desenvolvedor após o teste de nivelamento. Entendemos que em uma seleção podem existir dezenas ou centenas de participantes. Então aplique o teste para um número reduzido de participantes no qual você possa realizar este feedback. Na página da Tabnews, no tópico [Teste de conhecimento Power BI](https://www.tabnews.com.br/pietrofarias/teste-de-conhecimento-power-bi-para-avaliadores), os desenvolvedores poderão informar quais os avaliadores não estão retornando adequadamente estes feedbacks.

* As regras de cada _case_ são apenas sugestões. Cada _case_ é criado pela comunidade e entendendo o que deveria ser aplicado e o que poderá ser extraído desta aplicação. Então, saiba cobrar adequadamente o que está disponível para cada _case_.

* Caso queira modificar ou criar _cases_, você pode usar o próprio GitHub para poder usar no seu repositório ou ajudar a comunidade a centralizar estes cases aqui mesmo no repositório.

# Premissas para o DESENVOLVEDOR Avaliado
Entenda como será feito o nivelamento:
**1.** Em cada diretório existirá uma descrição do que deverá ser realizado e quais os pontos serão avaliados. Resolva apenas os cases no qual foi solicitado para nivelamento. Pois espera-se que você possua, no mínimo, os conhecimentos que estão sendo exigidos naquele case. Mais de um case poderá ser solicitado.

**2.** Você ocorrer de você apresentar a resolução de cada _case_ solicitado, mostrando os seguintes pontos:
| → Os principais desafios do _case_;
| → Quais as soluções técnicas que você usou para chegar no resultado;
| → Se solicitado, informar quais as documentações ou referências que usou para chegar na solução de algum item avaliado;


**3.** O envio do teste deverá seguir os requisitos da seção **[Requisitos para o envio do teste](#requisitos-para-o-envio-do-teste)**

**4.** Após o envio, você deverá receber um retorno da avaliação.
> `Nota 1` 
> **Este ponto é de grande relevância para todos os desenvolvedores. Caso não receba um feedback, poste oseu caso no tópico da TabNews: [Teste de conhecimento Power BI](https://www.tabnews.com.br/pietrofarias/teste-de-conhecimento-power-bi-para-avaliadores);**
> 
> `Nota 2`
> **Tenha o bom senso de que podem existir uma quantidade muito grande de avaliados e que os avaliadores precisam de um tempo para retornar cada um deles. As vezes este retorno podem demorar dias ou semanas. Sempre procure primeiro o avaliador antes de postar seu comentário sobre eles, solicitando um prazo ESTIMADO;**




# Requisitos para o envio do teste
Nesta seção, você encontrará os requisitos necessários para o envio do teste de nivelamento. Estes requisitos são necessários para que o avaliador receba um arquivo padronizado, fácil de receber e conectar as fontes de dados de cada _case_.

Seções:
* [Arquivos no formato PBIT](#arquivos-no-formato-pbit);
* [Usar os Parâmetros do Power Query (M)](#usar-os-parâmetros-do-power-query-m)

## Arquivos no formato PBIT
Os arquivos enviados para o solicitante da avaliação deve estar no formato PBIT. Para acessar a documentação da Microsoft referente a este requisito, acesse [Criar e usar modelos de relatório no Power BI Desktop - Power BI | Microsoft Learn](https://learn.microsoft.com/pt-br/power-bi/create-reports/desktop-templates)

![image](https://user-images.githubusercontent.com/24781333/218267775-af9ad173-51a3-4317-8392-f4946f60b5c2.png)


## Usar os Parâmetros do Power Query (M)
Ao abrir o arquivo PBIT, o avaliador terá que conectar as fontes de dados. Estas fontes de dados podem estar alocadas em diversas bases de dados. Alguns possuem endereço web ou de um diretório, usuários de acessos, token para api, endereços de servidores, base de cálculo ou muitos outros.

Todos estes parâmetros são necessários para poder saber se o desenvolvedor está usando as premissas e parâmetros necessários na realização do _case_, além de também fazer parte de uma boa prática no desenvolvimento.

Nas instruções de cada _case_ serão informados quais os parâmetros que devem ser criados. Para acessar a documentação da Microsoft referente aos parâmetros, acesse [Parâmetros de consulta M dinâmica no Power BI Desktop - Power BI | Microsoft Learn](https://learn.microsoft.com/pt-br/power-bi/connect-data/desktop-dynamic-m-query-parameters)

![image](https://user-images.githubusercontent.com/24781333/218271529-a64e365b-722e-40d9-9bb0-8274dee34e4d.png)
