# test

Name und Identifikationsnummer: UC 1.04 - Alarm bei Leistungsabweichung
Beschreibung: Der/Die Proband:in wird durch einen Leistungstest auf dem Ergometer durchgeführt. Sollte die erforderte Leistung nicht mehr erbracht werden, soll ein Alarmsignal gegeben werden.
Beteiligte Akteure: Diagnostiker:in, Proband:in
Status: in Arbeit
Verwendete Anwendungsfälle: UC 1.03 (Alarm bei zu hoher Herzfrequenz)
Auslöser: Überprüfung der Leistung des/der Patient:in, Verhinderung der Überforderung des/der Patient:in
Vorbedingungen: UC 1.01 (Probandin anlegen), UC 1.02 (Leistungstest anlegen)
Invarianten: Aufzeichnung der bis zum Abbruch erhobenen Daten
Nachbedingung/Ergebnis: Leistungstest wird gestoppt, Ergometer wird in Ruhemodus versetzt
Standardablauf: Alle Leistungsstufen werden nacheinander durchlaufen. Wird die erwünschte Leistung nicht mehr erbracht, wird ein Alarm ausgelöst und der Leistungstets wird abgebrochen/neugestartet. Daten werden gespeichert. 
Alternative Ablaufschritte: Widerstandswerte werden nicht verletzt. Herzfrequenz befindet sich nicht mehr im erwünschten Bereich. Leistungstets wird abgebrochen.  
Hinweise: keine 
Änderungsgeschichte: 0.01; 16.03.2024; Svenja Taft

