# EDI Mapping Studio – V0.2 (erster GitHub-Entwurf)

Lokaler HTML-Prototyp für die geplante EDI Mapping Library. **Keine Produktionssoftware.**

## Start
`index.html` im Browser öffnen. Keine Installation und kein Server nötig.

## Formate (11 Varianten)
- UBL 2.5
- ebInterface 6.1 Bund / AustriaPro
- SAP INVOICE ZINVOIC02 (Parserbericht)
- EBOR-V1
- Zeus CreditNoteV1 / ImmediateV1
- UN/EDIFACT INVOIC D.16B / D.23A / D.24A
- Amdocs ADX Flatfile V6.1 (Altova FlexText)

## Stand
- Formatnavigation und gemeinsame Oberfläche
- Einfacher lokaler XSD-/XML-Baum (einzelne Datei; eingeschränkte Typauflösung)
- Experimentelle MFT-Strukturübersicht
- Parserbericht als durchsuchbare Textzeilen, **noch keine IDoc-Semantik**
- Elementdetails und Suche

## Noch offen
- Vollständige XSD-Imports/Includes und Namespace-Auflösung
- ZIP-Import und Altova-EDIFACT-Config-/Segment-/Codelistenadapter
- Vollständiger FlexText-Parser und Flatfile-Instanzansicht
- IDoc-Parserbericht strukturiert auflösen
- EN16931 BT/BG, Mappingtabellen, Excel-Import, zellbezogene Kommentare/Dokumente
- Übernahme der früheren Viewer-Versionen V0.8/V0.5 und Tests

## Datenschutz / Lizenz
Dieses öffentliche Repository enthält **keine** internen Schemas, Parserberichte, Beispieldaten oder Altova-Standardbibliotheken. Dateien werden im Browser lokal gewählt. Bitte keine vertraulichen Dateien committen.
