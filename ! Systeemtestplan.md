Systeemtestplan Semester 6

























##
Naam: Rienk Engbrenghof

Studentnummer: 429059

Klas: S6-RB03T


# Introductie
In dit document wordt het plan opgesteld hoe het systeem getest gaat worden en in welke mate. Hierbij worden alle userstories die opgesteld zijn in het SAD, onder de loep genomen. Er worden prioriteiten aan gebonden en op basis daarvan worden ze getest. 
# Versiebeheer

|23/2/2022|Opzet testplan.|
| :- | :- |
|19/3/2022|Aanpassingen aan testplan.|
|20/4/2022|Feedback Marc toegepast.|

# Repositories
Link naar repository: https://github.com/Pretter-S6
# Inhoudsopgave


[1.	Testplan	5](#_Toc102983287)

[1.1	Productrisicoanalyse	5](#_Toc102983288)

[1.2	Teststrategie	5](#_Toc102983289)

[1.3	Logische testcases	6](#_Toc102983290)

[1.4	Unittesten en code coverage	6](#_Toc102983291)

[2.	Conclusie	7](#_Toc102983292)




1. # Testplan
   1. ## Productrisicoanalyse

|**Testdoel**|**Schade**|**Faalkans**|**Risicoklasse**|**Ernstklasse**|
| :- | :- | :- | :- | :- |
|Inloggen|2|2|4|B|
|Registreren|2|3|6|B|
|Iemand volgen|1|1|1|C|
|Iemand ontvolgen|1|1|1|C|
|Profiel beheren|1|2|2|C|
|Post plaatsen|1|2|2|C|
|Profiel bekijken|1|1|1|C|
|Foto toevoegen|2|3|6|B|
|Post liken|1|1|1|C|
|Post reageren|1|2|2|C|
|Uitloggen|1|1|1|C|
|Gebruikers zoeken|2|1|2|C|

Ernstklasse C: risicoklasse ≤ 2

Ernstklasse B: 2 < risicoklasse ≤ 6

Ernstklasse A: risicoklasse > 6

1. ## Teststrategie

|**Testdoel**|**PRA**|**UT**|**CT**|**IT**|**ST Han.**|**St Aut.**|
| :- | :- | :- | :- | :- | :- | :- |
|Inloggen|B|XX||X|XX|X|
|Registreren|B|XX|||XX|X|
|Iemand volgen|C|X||X|XX|X|
|Iemand ontvolgen|C|X||X|XX||
|Profiel beheren|C|||X|XX||
|Post plaatsen|C|XX|X|X|X||
|Profiel bekijken|C|||XX|X||
|Foto toevoegen|B|||XX|XX||
|Post liken|C|X||X|X||
|Post reageren|C|X||X|X||
|Uitloggen|C|||XX|XX||
|Gebruikers zoeken|C||X|XX|X||

**Afkortingen:** PRA= Product Risico Analyse, UT= Unittest, CT= Component test, IT= Integratie test en ST= Systeemtest.

De X staat voor de mate waarin het wordt getest, waarin driemaal X het maximale is.


1. ## Logische testcases

|**ID**|**Omschrijving**|
| :- | :- |
|TC-01|Gebruiker kan inloggen met geldige gegevens.|
|TC-02|Gebruiker kan niet inloggen met ongeldige gegevens.|
|TC-03|Gebruiker kan registeren met geldige gegevens.|
|TC-04|Gebruiker kan niet registeren met ongeldige gegevens.|
|TC-05|Gebruiker kan iemand volgen.|
|TC-06|Gebruiker kan iemand ontvolgen.|
|TC-07|Gebruiker kan zijn profiel beheren.|
|TC-08|Gebruiker kan een post plaatsen met geldige gegevens.|
|TC-09|Gebruiker kan geen post plaatsen met ongeldige gegevens.|
|TC-10|Gebruiker kan een profiel bekijken.|
|TC-11|Gebruiker kan een foto toevoegen aan zijn post.|
|TC-12|Gebruiker kan een post liken.|
|TC-13|Gebruiker kan een geldige reactie plaatsen bij een post.|
|TC-14|Gebruiker kan geen ongeldige reactie plaatsen bij een post.|
|TC-15 |Gebruiker kan uitloggen.|
|TC-16|Gebruiker kan een gebruiker zoeken met geldige gegevens.|
|TC-17|Gebruiker kan geen gebruiker zoeken met ongeldige gegevens.|

1. ## Unittesten en code coverage 
De code wordt gecoverd door sonarcloud, gegevens zijn nog niet relevant door de hoeveelheid code.

![](Aspose.Words.a08ffcdb-4e6c-4aa0-b935-1f343c749c5a.001.png)
1. # Conclusie

Systeemtestplan Semester 6 – Rienk Engbrenghof		 2
