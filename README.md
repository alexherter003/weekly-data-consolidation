# weekly-data-consolidation
Make.com automation to consolidate weekly data from 3 systems into Power BI dashboard

# Weekly Data Consolidation – Make.com Automation

## Projektbeschreibung
Automatisierung zur wöchentlichen Zusammenführung von Exportdaten 
aus drei verschiedenen Systemen in ein zentrales Google Sheet, 
verbunden mit einem Power BI Dashboard.

## Ablauf
1. Wöchentlicher Schedule-Trigger startet das Szenario
2. Clear Values Modul löscht alte Daten aus dem Master-Sheet
3. Router teilt den Prozess in 3 parallele Äste
4. Jeder Ast: Search Rows (Quelldaten lesen) → Add a Row (in Master-Sheet schreiben)
5. Power BI liest das Master-Sheet und aktualisiert das Dashboard
6. Fehlerbenachrichtigung per E-Mail bei Problemen

## Tools
- Make.com
- Google Sheets
- Microsoft Power BI

## Ziel
Manuelle wöchentliche Datenkonsolidierung vollständig automatisieren 
und Reporting-Zeit deutlich reduzieren.
