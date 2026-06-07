# Datensatz und Analyseskripte
## Bachelorarbeit: Einfluss von IT-Governance auf die Verwendung von Multifaktor-Authentifizierung in beruflichen und privaten Kontexten

**Autorin:** Andrea Ungerer  
**Studiengang:** IT-Infrastrukturmanagement (BITI-23BB), Hochschule Burgenland  
**Studienjahr:** 2025/26  
**Betreuer:** Wolfram Rinke

---

## Inhalt dieses Repositorys

Dieses Repository enthält den bereinigten Datensatz, den Orange-Workflow sowie die Python-Analyseskripte zur empirischen Erhebung der Bachelorarbeit. Die Umfrage wurde im April 2026 durchgeführt (N = 401 gültige Datensätze nach Qualitätskontrolle).

---

## Dateistruktur

```
├── MFA_Orange_N394_v2.xlsx        Bereinigter, kodierter Datensatz (N = 401)
├── BA_Ungerer_rev1_2205.ows       Orange Data Mining Workflow
├── mapping3.txt                   Codebuch: Variablennamen und Fragebogen-Items

└── README_Datensatz.md            Diese Datei
```

---

## Datensatz

Die Rohdaten wurden aus Microsoft Forms exportiert und anschließend bereinigt.
- Ausschluss von Teilnehmenden, die beide Qualitätskontrollfragen falsch beantwortet haben
- Alle Angaben sind vollständig anonymisiert, keine personenbezogenen Daten enthalten

Das Codebuch (mapping3.txt) erklärt die Variablennamen und ihre Entsprechung im Fragebogen.

---

### Orange Data Mining

Voraussetzungen: [Orange3](https://orangedatamining.com/) mit dem Add-on *Explain*

Den Workflow `BA_Ungerer_rev1_2205.ows` in Orange öffnen und `MFA_Orange_N394_v2.xlsx` als Datenquelle einbinden.

