---
title: "TeXFragment"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar TeX-fragment."
type: docs
weight: 1510
url: /sv/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

Representerar TeX-fragment.

Typen TeXFragment visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TeXFragment(text) | Initierar en ny instans av klassen TeXFragment |
| TeXFragment(text, remove_indents) | Initierar en ny instans av klassen TeXFragment |
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
| te_x_load_options_of_instance | Hämtar eller anger TeXLoadOptions som kommer att användas för inläsning (och rendering) av LaTeX i denna klassinstans.<br/>            Använd detta när det är nödvändigt att använda en specifik inställning för import av LaTeX för denna eller den andra instansen<br/>             (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad LaTeX eller en specifik laddare för externa resurser)<br/>            Om parametern är standard (null) kommer standardalternativen för LaTeX‑inläsning att användas. |
| latex_load_options_of_instance | Hämtar eller anger TeXLoadOptions som kommer att användas för inläsning (och rendering) av LaTeX i denna klassinstans.<br/>            Använd detta när det är nödvändigt att använda en specifik inställning för import av LaTeX för denna eller den andra instansen<br/>             (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad LaTeX eller en specifik laddare för externa resurser)<br/>            Om parametern är standard (null) kommer standardalternativen för LaTeX‑inläsning att användas. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| clone() | Klonar fragmentet. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

