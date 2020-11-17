#Edgelist								
from	Definiert den Sender. Entspricht ID in der Nodelist. KeineSonderzeichen, nur ein Wort.							
to	Definiert den Empfänger. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.							
relation	(Art der Beziehung zu einer Organisation) 1=Hauptamt 2=Nebenamt 3=Ehrenamt 4=Mitgliedschaft 5=einmaligeentgeldliche Tätigkeit 6=Sonstiges 7=Bundesausschussmitgliedschaft 8=Ministeriumszugehörigkeit 							
duration	(Dauer der Tätigkeit) 1=0-3Jahre 2=3-6Jahre 3=6-9Jahre 4=9-12Jahre 5=12-15Jahre 6=mehrals15Jahre							
status	(aktive Tätigkeit) 1=Ja 2=Nein							
health	(Tätigkeit im Gesundheitssektor (im weitesten Sinne)) 1=Ja 2=Nein							
								
#Nodelist								
id	Identische ID wie aus der edgelist zur Identifikation der Knoten.							
label	Vollständige Bezeichnung der Knoten.							
sex	(Geschlecht) 1=weiblich 2=männlich 3=divers							
type	1=Person 2=Organisation							
type_detail	2=Unternehmen 3=Verein/Organisation 4=politischeInstitution 5=Stiftung							
age	(Alter der Mitglieder) 1=20-30Jahre 2=31-40Jahre 3=41-50Jahre 4=51-60Jahre 5=61-70Jahre 6=71-80Jahre 7=81-90Jahre 8=tot							
birth	(Geburtsjahr der Mitglieder) 1=1930-1940 2=1941-1950 3=1951-1960 4=1961-1970 5=1971-1980 6=1981-1990 7=1991-2000							
education	(Höchster Bildungsabschluss) 1=Hauptschulabschluss 2=MittlereReife 3=Fachhochschulreife 4=Abitur 5=Berufsausbildung 6=Bachelor 7=Master 8=Staatsexamen 9=Promotion							
education_background	(Kategorie der Berufsausbildung) 1=Wirtschaft 2=Politik 3=Medizin 4=Soziales 5=Sonstiges (Jura, Journalismus/ Kommunikation)							
background	(Tätigkeiten im Gesundheitssektor) 1=Ja 2=Nein							
party	(Parteizugehörigkeit der Mitglieder) 1=CDU/CSU 2=SPD 3=DIELINKE 4=DIEGRÜNEN 5=FDP							
state	(Verortung nach Bundesländern) 1=Baden-Württemberg 2=Bayern 3=Berlin 4=Brandenburg 5=Bremen 6=Hamburg 7=Hessen 8=Mecklenburg-Vorpommern 9=Niedersachsen 10=Nordrhein-Westfahlen 11=Rheinland-Pfalz 12=Saarland 13=Sachsen 14=Sachsen-Anhalt 15=Schleswig-Holstein 16=Thüringen							
function	(Funktion Bundesgesundheitsministerium) 1=Bundesgesundheitsminister 2=Staatssekretär 3=Drogenbeauftragte*r 4=Sonstige							
health_sector	(Institution im Gesundheitssektor) 1=Ja 2=Nein							
health_category	(Geschäftszweige im Gesundheitssektor) 1=Pharmakonzerne 2=Medizintechnikhersteller 3=Krankenhäuser 4=Verband/Stiftung 5=Sonstiges							
period	(Legislaturperiode) 1=2005-2009 2=2009-2013 3=2013-2017 4=2017-2021							
								
99	DefiniertfehlendeWerte.