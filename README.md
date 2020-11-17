Codebuch Stand 2020-11-17
erstellt von Jasmin Maya, Nora Schwarz, Verena Nagel, Julian Hammerstein, Samuel Müller, Janina Hofmann
(jm133@hdm-stuttgart.de, ns136@hdm-stuttgart.de, vn009@hdm-stuttgart.de, jh229@hdm-stuttgart.de, sm222@hdm-stuttgart.de, jh231@hdm-stuttgart.de)

Inhalt

    Edges.csv (Edgelist)
    Nodes.csv (Nodelist)
    Codebuch.rm (Codierung der Datensätze)

EDGE-Attribute

from
(Definiert den Sender. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort)

to
(Definiert den Empfänger. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.)


relation 
(Art der Beziehung zu einer Institution)
1 = Hauptamt
2 = Nebenamt
3 = Ehrenamt
4 = Mitgliedschaft
5 = einmalige entgeldliche Tätigkeiten
6 = Sonstiges
7 = Bundesausschussmitgliedschaft
8 = Ministeriumszugehörigkeit

duration
(Dauer der Tätigkeit)
1 = 0-3 Jahre
2 = 3-6 Jahre
3 = 6-9 Jahre
4 = 9-12 Jahre
5 = 12-15 Jahre
6 = mehr als 15 Jahre

status 
(aktiv)
1 = Ja
2 = Nein

health
(Tätigkeit im Gesundheitssektor(im weitesten Sinne))
1 = Ja
2 = Nein


NODE-Attribute

id
(jede ID entspricht einer Institution oder einem Mitglied des Gesundheitsministeriums)

label
(vollständige Bezeichnung der Knoten)

sex
(Geschlecht)
1 = weiblich
2 = männlich
3 = divers

type
(Person oder Organisation)
1 = Person
2 = Organisation


type_detail
(Art der Organisation)
2 = Unternehmen
3 = Verein/Organisation
4 = politische Institution
5 = Stiftung

age
(Alter der MitgliederInnen)
1 = 20-30 Jahre
2 = 31-40 Jahre
3 = 41-50 Jahre
4 = 51-60 Jahre
5 = 61-70 Jahre
6 = 71-80 Jahre
7 = 81-90 Jahre
8 = tot

birth
(Geburtsjahr der MitgliederInnen)
1= 1930-1940 
2= 1941-1950 
3= 1951-1960 
4= 1961-1970 
5= 1971-1980 
6= 1981-1990 
7= 1991-2000

education
(höchster Bildungsabschluss)
1 = Hauptschulabschluss
2 = Mittlere Reife
3 = Fachhochschulreife
4 = Abitur
5 = Berufsausbildung
6 = Bachelor
7 = Master
8 = Staatsexamen
9 = Promotion

education_background
(Kategorie der Berufsausbildung)
1= Wirtschaft 
2= Politik 
3= Medizin 
4= Soziales 
5= Sonstiges (Jura, Journalismus/ Kommunikation etc.)

background
(Tätigkeiten im Gesundheitssektor)
1 = Ja
2 = Nein

party
(Parteizugehörigkeit der MitgliederInnen)
1 = CDU/CSU
2 = SPD
3 = DIE LINKE
4 = DIE GRÜNEN
5 = FDP

state
(Verortung nach Bundesländern)
1 = Baden-Württemberg
2 = Bayern
3 = Berlin
4 = Brandenburg
5 = Bremen
6 = Hamburg
7 = Hessen
8 = Mecklenburg-Vorpommern
9 = Niedersachsen
10 = Nordrhein-Westfahlen 
11 = Rheinland-Pfalz
12 = Saarland 
13 = Sachsen
14 = Sachsen-Anhalt
15 = Schleswig-Holstein
16 = Thüringen

function
(Funktion im Bundesgesundheitsministerium)
1 = Bundesgesundheitsminister
2 = Staatssekretär
3 = Drogenbeauftragte*r
4 = Sonstige

health_sector
(Institution im Gesundheitssektor)
1 = Ja
2 = Nein

health_category
(Geschäftszweige im Gesundheitssektor) 
1= Pharmakonzerne 
2= Medizintechnikhersteller 
3= Krankenhäuser 
4= Verband/Stiftung 
5= Sonstiges

period
(Legislaturperiode)
1 = 2005-2009
2 = 2009-2013
3 = 2013-2017
4 = 2017-2021

99 = Definiert fehlende Werte
