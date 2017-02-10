#Bestandteile
- (S) Login
- (S) Dashboard
  - (E) Menü
  - (E) Nachrichtenübersicht
  - (E) Terminübersicht
  - (E) Aufgabenübersicht?
- (S) Dateisystem
  - (E) Öffentliche Dateien
  - (E) Private Dateien
  - (E) Geteilte Dateien
  - (S) Datei hochladen
  - (S) Datei bearbeiten?
- (S) Nachrichtenbereich
  - (E) Channels, denen ich angehöre
  - (E) Andere Channels
  - (E) Darstellung des Channels
  - (E) Texteingabe
  - (S) Verwaltung der Channels
- (S) Terminbereich
  - (S) Anstehende Termine
  - (S) Genaue Terminansicht
  - (S) Termin erstellen
- (S) Einstellungen
  - (E) Bereiche & Aufgaben
  - (E) Pushnachrichten, Emails, ...
  - (E) persönliche Informationen
  - (E) Management von Mitgliedern
  - (E) Dateisynchoronisation
=> 12 Seiten

#Funktionsweise Nachrichten
- Pro Channel eine XML-Datei
- Sobald Enter:
-- 
-- in einer Firebase-Datenbank wird der Channelzähler inkrementiert

#Herausforderungen
- Speichern & Echtzeitsynchronisation von Dateien
- Desktoppushnachrichten

#Langfristige Funktionswünsche
- Gruppieren von Channels
- Nicht jeder kann immer direkt in jedem Channel posten (Rechtetrennung Lesen/Schreiben)
- Nicht alle Nachrichten werden sofort geladen
- Wer schreibt und wer hat gelesen?














