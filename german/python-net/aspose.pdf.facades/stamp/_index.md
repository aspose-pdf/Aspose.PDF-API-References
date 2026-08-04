---
title: "Stamp"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die einen Stempel darstellt."
type: docs
weight: 410
url: /de/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Klasse, die einen Stempel darstellt.

Der Typ Stamp stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Stamp() | Initialisiert eine neue Instanz der Klasse Stamp |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| stamp_id | Liest oder setzt den Bezeichner des Stempels. |
| quality | Liest oder setzt die Qualität des Bildstempels in Prozent. Gültige Werte 0..100%. |
| opacity | Liest oder setzt die Deckkraft des Stempels. |
| page_number | Liest oder setzt die Seitennummer. |
| pages | Liest oder setzt ein Array mit den Nummern der Seiten, die vom Stempel betroffen sind. <br/>            Wenn Pages = null, sind alle Seiten des Dokuments betroffen. |
| rotation | Liest oder setzt die Drehung des Stempels in Grad. |
| is_background | Liest oder setzt den Hintergrundstatus. Wenn true, wird der Stempel als Hintergrund der gespannten Seite platziert.<br/>            Standardmäßig ist er auf false gesetzt. |
| blending_space | Liest oder setzt einen BlendingColorSpace-Wert, der einen Farbraum definiert <br/>            der verwendet wird, um Transparenz- und Mischvorgänge auf der Seite durchzuführen. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Legt die PDF-Datei und die Seitennummer fest, die als Stempel verwendet werden. |
| bind_pdf(pdf_stream, page_number) | Legt die PDF-Datei und die Seitennummer fest, die als Stempel verwendet werden. |
| bind_image(image_file) | Legt das Bild als Stempel fest. |
| bind_image(image) | Legt das Bild fest, das als Stempel verwendet wird. |
| bind_logo(formatted_text) | Legt den Text als Stempel fest. |
| bind_text_state(text_state) | Setzt den Textzustand des Stempeltexts. |
| set_origin(origin_x, origin_y) | Setzt die Position auf der Seite, an der der Stempel platziert wird. |
| set_image_size(width, height) | Setzt die Größe des Bildstempels. Das Bild wird anhand der angegebenen Werte skaliert. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

