﻿## Финальный проект по эконометрике: «Изучение и моделирование шоков на рынке нефти и их влияние на макроэкономические показатели на примере Германии»

Работа опирается на статью Cologni, A., & Manera, M. (2008). Oil prices, inflation and interest rates in a structural cointegrated VAR model for the G-7 countries. Energy Economics, 30(3), 856–888. doi:10.1016/j.eneco.2006.11.001 

В ней рассматривается построение модели SVAR для стран G7 для группы показателей:

- Доходность по краткосрочным гос.облигациям, % доходность
- CPI(Индекс потребительских цен), индекс
- Реальный ВВП в постояных ценах, миллион. национальная валюта
- Денежный агрегатор(M1), 
- Отношение национальной курсы валюты к СДР(Специальные права заимствования), отношение
- Биржевая стоимость нефти марки Brent, долл. 

Все данные квартальные. В статье рассматривался период(1980Q1 - 2003Q3)

Затем в статье рассматривается модель VECM для этих же показателей и моделируются шоки, которые оказывают изменение цены на нефть и на остальные показатели. 

В итоговой работе рассмотрены упрощенные модели VAR, VECM,  а также модель ARIMA и модели ECM, в соответствии с планом итогового проекта. 

В проектной работе для построения моделей используются те же переменные, но взятые с 1994Q и до 2018Q2, на примере Германии. Также логирифмируются некоторые переменные, исходя из экономического смысла. Главная цель работы - составить модель распространения шоков цены на нефть на другие макроэкономические факторы, в особенности - на доходность гос. облигаций. Также в конце будут сравнены полученные результаты в проектной работе на современных данных с выводами авторов статьи и сделаны соответсвующие выводы.

Источники информации:

- Доходность по краткосрочным гос.облигациям - терминал Bloomberg(тикер: GDBR2:IND)
- CPI - worldbank
- Реальный GDP - eurostat(запрос: Chain linked volumes)
- Денежный агрегатор(M1) - IMF
- Отношение национальной курсы валюты к СДР - eurostat
- Биржевая стоимость нефти марки Brent - терминал Bloomberg(тикер: CO1:COM)

