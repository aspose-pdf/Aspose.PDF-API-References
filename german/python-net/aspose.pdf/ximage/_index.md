---
title: "XImage"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die ein Bild-X-Object darstellt."
type: docs
weight: 1680
url: /de/python-net/aspose.pdf/ximage/
---

## XImage class

Klasse, die ein Bild-X-Object darstellt.

Der XImage-Typ stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| contains_transparency | Wenn das Bild Transparenz enthält, wird true zurückgegeben; andernfalls false. |
| grayscaled | Liest die graustufige Version des Bildes. |
| filter_type | Liest den Bildfiltertyp. |
| breite | Liest die Breite des Bildes. |
| höhe | Liest die Höhe des Bildes. |
| Name | Liest oder setzt den Bildnamen. Bitte beachten Sie, dass das Ändern des Namens eines Bildes, das in Seiteninhalten referenziert wird, das Dokument inkorrekt machen kann. Verwenden Sie in diesem Fall die Methode XImage.Rename. |
| Metadaten | Metadaten des Bildes. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| save(stream) | Speichert Bilddaten in einen Stream als JPEG-Bild. |
| save(stream, format) | Speichert das Bild in einen Stream mit dem gewünschten Format. |
| save(stream, resolution) | Speichert Bilddaten in einen Stream als JPEG-Bild mit angegebener Auflösung. |
| save(stream, format, resolution) | Speichert das Bild in einen Stream mit dem gewünschten Format und angegebener Auflösung. |
| rename(name) | Benennt das Bild um und ersetzt alle Verweise auf das Bild durch den neuen Namen |
| get_color_type() | Gibt den Farbtyp des Bildes zurück. |
| detect_color_type(bmp) | Gibt den Farbtyp des Bildes zurück. |
| is_the_same_object(image) | Gibt true zurück, wenn beide Bilder auf dasselbe Objekt verweisen. |
| get_name_in_collection() | Gibt den Namen des Bildes in der ints-Sammlung zurück. |
| to_stream() | Gibt den ursprünglichen Bild-Stream zurück. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

