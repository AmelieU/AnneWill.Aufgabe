# Codebuch für Testprojekt

Wir untersuchen ein Netztwerk der Gäste von Anne WilL und ihrer Parteizugehörigkeit.

### Nodelist
- id = Kleingeschriebe Initialen von Vor- und Nachnamen. Bei Folgen und Parteien werden kleingeschriebene Kürzel verwendet.
- name = Vollständiger Name des Gastes, der Partei oder Name der Sendung.
- party = Parteizugehörigkeit des jeweiligen Gastes, falls vorhanden.
- sector = Gesellschaftlicher bzw. beruflicher Bereich des Gastes
- country = Land, dem der Gast zugeordnet ist.

### Edgelist
- from = Gast
- to = Episodennummer oder die Partei
- relationship = Art der Beziehung: 
  - 1 = Gast in jeweiliger Episode
  - 2 = Gast in Mitglied in jeweiliger Partei
