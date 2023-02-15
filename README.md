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
