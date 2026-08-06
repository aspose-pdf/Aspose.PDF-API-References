---
title: "Tabell"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en tabell som kan läggas till på sidan."
type: docs
weight: 1480
url: /sv/python-net/aspose.pdf/table/
---

## Table class

Representerar en tabell som kan läggas till på sidan.

Tabell-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Table() | Initierar en ny instans av Tabell-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| vertical_alignment | Hämtar eller anger en vertikal justering av stycket. |
| horizontal_alignment | Hämtar eller anger en horisontell justering av stycket. |
| margin | Hämtar eller anger en yttre marginal för stycket (för pdf‑generering) |
| is_first_paragraph_in_column | Hämtar eller anger ett bool‑värde som indikerar om detta stycke kommer att vara i nästa kolumn.<br/>            Standard är false.(för pdf‑generering) |
| is_kept_with_next | Hämtar eller anger ett bool‑värde som indikerar om aktuellt stycke förblir på samma sida tillsammans med nästa stycke.<br/>            Standard är false.(för pdf‑generering) |
| is_in_new_page | Hämtar eller anger ett bool‑värde som tvingar detta stycke att genereras på en ny sida.<br/>            Standard är false.(för pdf‑generering) |
| is_in_line_paragraph | Hämtar eller anger om ett stycke är inline.<br/>            Standard är false.(för pdf‑generering) |
| hyperlänk | Hämtar eller anger fragment‑hyperlänken (för pdf‑generatorn). |
| z_index | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex <br/>            kommer att placeras ovanför grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ <br/>            ZIndex kommer att placeras bakom texten på sidan. |
| background_color | Hämtar eller anger tabellens bakgrundsfärg |
| break_text | Hämtar eller anger bryttext för tabellen. |
| corner_style | Hämtar eller anger stilarna för kantens hörn |
| repeating_rows_style | Hämtar stilen för upprepande rader. |
| repeating_columns_count | Hämtar eller anger maximalt antal kolumner för tabellen. |
| repeating_rows_count | Hämtar antalet första rader som upprepas på flera sidor. |
| column_widths | Hämtar kolumnbredderna för tabellen. |
| broken | Hämtar eller anger tabellens vertikala avbrott; |
| default_cell_border | Hämtar standardcellens kant; |
| default_column_width | Hämtar standardcellens kant; |
| rader | Hämtar raderna i tabellen. |
| kant | Hämtar eller anger kanten. |
| default_cell_padding | Hämtar eller anger standardcellens utfyllnad. |
| default_cell_text_state | Hämtar eller anger standardtexttillståndet för cellen. |
| justering | Hämtar eller anger tabellens justering. |
| left | Hämtar eller anger tabellens vänstra koordinat. |
| top | Hämtar eller anger tabellens övre koordinat. |
| is_broken | Hämtar eller anger att tabellen är bruten - kommer att trunkeras för nästa sida. |
| is_borders_included | Hämtar eller anger kant inkluderad i kolumnbredder. |
| column_adjustment | Hämtar eller anger tabellens kolumnjustering. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Klona tabellen. |
| get_width() | Hämta bredd. |
| get_height(parent_page) | Hämta höjd. |
| set_column_text_state(col_number, text_state) | Ställ in höjd. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importerar en endimensionell array med data till tabellen. Importen går en cell per varje array‑element och<br/>              startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader<br/>              fortfarande saknas (dvs. mål‑tabellen är för liten för att rymma all data), kommer nödvändiga rader att skapas |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

