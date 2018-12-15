# apitest
NodeJs App, which create comparasion over requests between many the same applications on DEVOPS environment: local/test/live

## Jakie rozwizania wybrac?
+ API nie powinno bazować bezpośrednio na Bazie danych, bo dane będą takie same
+ Test ma sprawdzać działanie kodu, a nie danych z bazy danych

### unitetest, funkcjonalny test
Najszybsze testy, ale 
- nie pozwalają na porównanie dwóch systemów, np lokalnego i produkcjynego

### backend-api
wywoluje requests bazujac na API i JSON
+ konieczne jest stworzenie API do pobierania danych, ale w przyszłości można też to API wykorzystać do apikacji
+ szybki czas testowania, 100Requestach, rzędu minuty


### frontend-api
pobiera html, cezka na zaladowanie, parsuje i porownuje konkretne wartosci przez xpath
+ latwe do zaimplementowania, ale trzeba podac klasy lub adresy, ktore ma porównywać
+ długi czas testowania, przy 100Requestach kilkanaście minut

## environment 
unitApi.yaml

+ typescript
+ visualstudio
+ nodejs
+ api

https://code.visualstudio.com/docs/languages/typescript


## Solution is based on scenario



## One Time Application

+ start as test:

    return 
      status: false/true
      errors:
      info:
  


### json config

+ sqllite to save json data
  + get server data
    + many servers
      + credentials
      
      
      
url

{

}



urls generator

schema
  + domain
  + url schema
  + model
  
data 
  + url
  + input json variable
  + output json content
