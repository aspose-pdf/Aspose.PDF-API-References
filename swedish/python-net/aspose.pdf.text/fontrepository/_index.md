---
title: "FontRepository"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt.<br/>             Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt."
type: docs
weight: 130
url: /sv/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Utför teckensnittssökning. Söker i systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt.<br/>             Tillhandahåller också funktionalitet för att öppna anpassade teckensnitt.

FontRepository-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| FontRepository() | Initierar en ny instans av klassen FontRepository |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| substitutioner | Hämtar samlingen av teckensnittssubstitutionsstrategier. |
| källor | Hämtar samlingen av teckensnittskällor. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| find_font(font_name) | Söker och returnerar teckensnitt med angivet teckensnittsnamn. |
| find_font(font_name, ignore_case) | Söker och returnerar teckensnitt med angivet teckensnittsnamn, med eller utan hänsyn till skiftlägeskänslighet. |
| find_font(font_family_name, stl) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil. |
| find_font(font_family_name, stl, ignore_case) | Söker och returnerar teckensnitt med angivet teckensnittsnamn och teckensnittsstil <br/>             med eller utan hänsyn till skiftlägeskänslighet. |
| open_font(font_stream, font_type) | Öppnar teckensnitt med angiven teckensnittström. |
| open_font(font_file_path) | Öppnar teckensnitt med angiven sökväg till teckensnittfil. |
| open_font(font_file_path, metrics_file_path) | Öppnar teckensnitt med angiven sökväg till teckensnittfil. |
| load_fonts() | Laddar systeminstallerade teckensnitt och standard‑Pdf‑teckensnitt. Denna metod är utformad för att snabba upp teckensnittsladdningsprocessen.<br/>            Som standard laddas teckensnitt vid första begäran om ett teckensnitt. Användning av denna metod laddar system‑ och standard‑Pdf‑teckensnitt<br/>            omedelbart innan något Pdf‑dokument öppnas. |
| reload_fonts() | Laddar om alla teckensnitt som anges av egenskapen [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

