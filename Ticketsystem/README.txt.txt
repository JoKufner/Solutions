Vorgenen Beim Import

1. Importieren der Sharepoint-Liste in eine geeignete Sharepoint-Seite
1.1 Die Lookup-Referenzen der Tickets-Liste (Status und Module) bitte nicht mit importieren (Lookups funktionieren mit dem CSV-Import noch nicht)
1.2 Manuelle Anlage der LookUp-Referenzen Status und Modul in der Tabelle Tickets

2. Import der Solution in eine beliebige Umgebung
2.1 Eingabe SharepointPage (Umgebungsvariable). Dies ist die Sharepoint-Seite, für welche die Listen importiert wurden. Bsp.: https://<deine-domain>.sharepoint.com/<Seitenname>
2.2 Eingabe Umgebungsvariable TicketsListID: ID der SharePoint Liste Tickets
2.3 Eingabe Umgebungsvariable ModuleListID: ID der SharePoint Liste Module
2.4 Eingabe Umgebungsvariable StatusListID: ID der SharePoint Liste Status

3. Anpassen der Datenquelle in der PowerApp
3.1 Öffne die PowerApp über die importierte Solution.
3.2 Wechsle in den Bereich Daten und lösche die Datenquelle "Tickets"
3.3 Füge die neu angelegte Liste "Tickets" im Bereich der Daten hinzu. Die neue Datenquell muss auch "Tickets" heißen
3.4 Speichern und Veröffentlichen.