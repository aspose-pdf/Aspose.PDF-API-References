---
title: "PdfPageStamp"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt einen Stempel dar, der eine PDF-Seite als Stempel verwendet."
type: docs
weight: 1230
url: /de/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

Klasse stellt einen Stempel dar, der eine PDF-Seite als Stempel verwendet.

Der PdfPageStamp-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfPageStamp(pdf_page) | Initialisiert eine neue Instanz der PdfPageStamp-Klasse |
| PdfPageStamp(file_name, page_index) | Initialisiert eine neue Instanz der PdfPageStamp-Klasse |
| PdfPageStamp(stream, page_index) | Initialisiert eine neue Instanz der PdfPageStamp-Klasse |
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
| pdf_page | Liest oder setzt die Seite, die als Stempel verwendet wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| put(page) | Stempel auf der angegebenen Seite platzieren. |
| set_stamp_id(value) | Setzt die Stempel‑ID. |
| get_stamp_id() | Gibt die Stempel‑ID zurück. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

