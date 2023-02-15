# Projeto de previsão de vendas

Este projeto trata-se da previsão de vendas de uma rede farmacêutica Rossmann com mais de 3000 lojas em 7 países da Europa, da qual a base de dados é disponibilizada na plataforma [Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales).

### Objetivos
- Análise exploratória de dados
- Implementação de modelos com melhor performance que a média
- Previsão do volume de vendas dos próximos 2 meses

### Perfil dos dados
|Variável|Descrição|
|-|-|
|Store|Loja com identificação única
|Sales|Volume de vendas do dia
|Customers|Clientes do dia
|Open|Indicação se a loja está aberta(1) ou não(0) 
|StateHoliday|Feriados públicos (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
|SchoolHoliday|Feriados escolares
|StoreType|Tipo de loja, entre 4 perfis (a, b, c, d)
|Assortment|Tipo de sortimento (a = basic, b = extra, c = extended)
|CompetitionDistance|Distância em metros entre a concorrência mais próxima
|CompetitionOpenSince|Data(mês/ano) em que a concorrência mais próxima abriu
|Promo|Indica a existência(1) ou não(0) de promção no dia
|Promo2|Indica se a loja está(1) ou não(0) participando de uma promoção extendida
|Promo2Since|Data em que a loja começou a participar da promoção extendida
|PromoInterval|Indica os intervalos de meses em que a loja participou da Promo2

### Resultados obtidos
![image](https://user-images.githubusercontent.com/84376824/219048648-54807712-0784-4800-b9c2-5ce480c5806e.png)

![image](https://user-images.githubusercontent.com/84376824/219047661-2f35f2b7-2fa7-45d7-afce-c3b2f03e897e.png)

##### Performance dos modelos
![image](https://user-images.githubusercontent.com/84376824/219047219-7656c89c-2be9-4631-9527-cb8b9e58e824.png)

##### Performance do XGBoost após o fine tuning dos parâmetros
![image](https://user-images.githubusercontent.com/84376824/219051588-d5722957-8879-4e17-8204-cffe9f5fbe2d.png)

### [Link para o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzQ1ODdiYjgtYTIwNC00NDI3LTkwZWItZDFkNGEyYzgyMjhjIiwidCI6IjNjMGE4OTcxLTVkYmItNDJkNi05ZTBmLTUyM2IxZTcyN2Q2MSJ9) feito com o PowerBI contendo uma visão geral das vendas.

### Veja o projeto completo no [jupyter notebook](https://github.com/katsuyosh/dsprod/blob/main/notebooks/notebookCiclo_01.ipynb), disponível no atual repositório.
