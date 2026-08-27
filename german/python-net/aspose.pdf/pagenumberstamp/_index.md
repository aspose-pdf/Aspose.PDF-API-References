---
title: "PageNumberStamp"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt die Seitenzahlmarkierung dar und wird zum Nummerieren von Seiten verwendet."
type: docs
weight: 1140
url: /de/python-net/aspose.pdf/pagenumberstamp/
---

## PageNumberStamp class

Stellt die Seitenzahlmarkierung dar und wird zum Nummerieren von Seiten verwendet.

Der PageNumberStamp-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PageNumberStamp(format) | Initialisiert eine neue Instanz der PageNumberStamp-Klasse |
| PageNumberStamp() | Initialisiert eine neue Instanz der [PageNumberStamp](/pdf/python-net/aspose.pdf/pagenumberstamp/) Klasse. Das Format ist auf "#" gesetzt. |
| PageNumberStamp(formatted_text) | Initialisiert eine neue Instanz der PageNumberStamp-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| background | Setzt oder liest einen booleschen Wert, der angibt, ob der Inhalt als Hintergrund gestempelt wird.<br/>            Wenn der Wert true ist, wird der Stempelinhalt unten platziert.<br/>            Standardmäßig ist der Wert false, der Stempelinhalt wird oben platziert. |
| opacity | Setzt oder liest einen Wert, der die Deckkraft des Stempels angibt. Der Wert liegt zwischen 0,0 und 1,0.<br/>            Standardmäßig ist der Wert 1,0. |
| outline_opacity | Setzt oder liest einen Wert, der die Deckkraft der Stempelumrandung angibt. Der Wert liegt zwischen 0,0 und 1,0.<br/>            Standardmäßig ist der Wert 1,0. |
| outline_width | Setzt oder liest einen Wert für die Breite der Stempelumrandung.<br/>            Standardmäßig ist der Wert 1,0. |
| rotate | Setzt oder liest die Drehung des Stempelinhalts gemäß den Werten von [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/>            Hinweis: Diese Eigenschaft dient zum Festlegen von Winkeln, die Vielfache von 90 Grad sind (0, 90, 180, 270 Grad).<br/>            Um einen beliebigen Winkel festzulegen, verwenden Sie die Eigenschaft RotateAngle. <br/>            Wenn der Winkel, der durch ArbitraryAngle festgelegt wird, kein Vielfaches von 90 ist, gibt die Eigenschaft Rotate den Wert Rotation.None zurück. |
| x_indent | Horizontale Stempelkordinate, beginnend von links. |
| y_indent | Vertikale Stempelkordinate, beginnend vom unteren Rand. |
| horizontal_alignment | Setzt oder liest die horizontale Ausrichtung des Stempels auf der Seite. |
| vertical_alignment | Setzt oder liest die vertikale Ausrichtung des Stempels auf der Seite. |
| left_margin | Setzt oder liest den linken Rand des Stempels. |
| right_margin | Liest oder setzt den rechten Rand des Stempels. |
| bottom_margin | Liest oder setzt den unteren Rand des Stempels. |
| top_margin | Liest oder setzt den oberen Rand des Stempels. |
| zoom_x | Horizontaler Zoomfaktor des Stempels. Ermöglicht das horizontale Skalieren des Stempels. |
| breite | Gewünschte Breite des Stempels auf der Seite. |
| höhe | Gewünschte Höhe des Stempels auf der Seite. |
| zoom_y | Vertikaler Zoomfaktor des Stempels. Ermöglicht das vertikale Skalieren des Stempels. |
| zoom | Zoomfaktor des Stempels. Ermöglicht das Skalieren des Stempels.<br/>            Bitte beachten Sie, dass das Paar der Eigenschaften ZoomX und ZoomY es ermöglicht, den Zoomfaktor für jede Achse separat einzustellen. <br/>            Das Setzen dieser Eigenschaft ändert sowohl die Eigenschaften ZoomX als auch ZoomY. <br/>            Wenn ZoomX und ZoomY unterschiedlich sind, gibt die Zoom‑Eigenschaft den Wert von ZoomX zurück. |
| rotate_angle | Liest oder setzt den Rotationswinkel des Stempels in Grad.<br/>            Diese Eigenschaft ermöglicht das Setzen eines beliebigen Rotationswinkels. |
| draw | Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als Grafikoperatoren gezeichnet, und wenn draw = false, wird der Stempel als Text gezeichnet. |
| treat_y_indent_as_base_line | Definiert den Koordinatenursprung für das Platzieren von Text.<br/>            Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true) wird der YIndent‑Wert als Textgrundlinie behandelt.<br/>            Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false) wird der YIndent‑Wert als Unterkante (Deszendentlinie) des Textes behandelt. |
| word_wrap | Definiert den Zeilenumbruch. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text in mehrere Zeilen umgebrochen, um in die angegebene Breite zu passen. Standardwert: false. |
| justify | Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, werden sowohl die linke als auch die rechte Textkante ausgerichtet. Standardwert: false. |
| Skalierung | Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text skaliert, um in die angegebene Breite zu passen. |
| Wert | Liest oder setzt den Zeichenkettenwert, der als Stempel auf der Seite verwendet wird. |
| text_state | Liest die Texteigenschaften des Stempels. Siehe [text_state](/pdf/python-net/aspose.pdf/textstamp/) für Details. |
| text_alignment | Ausrichtung des Textes innerhalb des Stempels. |
| max_row_width | Maximale Zeilenhöhe für die WordWrap-Option. |
| format | String-Wert zum Stempeln von Seitenzahlen. <br/>            Der Wert muss das Zeichen '#' enthalten, das im Stempelvorgang durch die Seitenzahl ersetzt wird. |
| starting_number | Liest oder setzt den Wert der Startseitennummer. Andere Seiten werden ab diesem Wert nummeriert. |
| numbering_style | Nummerierungsstil, der von diesem Stempel verwendet wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| put(page) | Fügt die Seitenzahl hinzu. |
| set_stamp_id(value) | Setzt die Stempel‑ID. |
| get_stamp_id() | Gibt die Stempel‑ID zurück. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

