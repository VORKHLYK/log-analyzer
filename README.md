# Log-Analyzer: Verdächtige Logins finden
Ein kleines Python-Projekt, das ich zum Lernen gemacht habe.

Was macht das Programm?

Das Programm liest eine Log-Datei (ein Protokoll von Login-Versuchen). Es zählt, wie oft ein Login pro IP-Adresse fehlgeschlagen ist. Wenn eine IP-Adresse 3 oder mehr Fehlversuche hat, markiert das Programm sie als verdächtig. So sieht ein einfacher Brute-Force-Angriff (Passwörter durchprobieren) im Protokoll aus.

Was habe ich benutzt?
- Python (in Google Colab)
- Schleifen ('for') und Bedingungen ('if')
- Strings ('split', 'strip')
- Dictionary zum Zählen
- Dateien lesen ('with open')

Was habe ich gelernt?

Ich habe gelernt, wie Log-Dateien aufgebaut sind und wie man mit Python Daten auswertet. Die Daten sind erfunden, es sind keine echten Personen betroffen.

