---
title: "XImage"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen som representerar bild X-Object."
type: docs
weight: 1680
url: /sv/python-net/aspose.pdf/ximage/
---

## XImage class

Klassen som representerar bild X-Object.

Typen XImage exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| contains_transparency | Om bilden innehåller transparens returneras true; annars false. |
| grayscaled | Hämtar gråskalig version av bilden. |
| filter_type | Hämtar bildfiltertyp. |
| bredd | Hämtar bildens bredd. |
| höjd | Hämtar bildens höjd. |
| name | Hämtar eller anger bildens namn. Observera att om du ändrar namnet på bilden som har referenser i sidinnehållet kan dokumentet bli felaktigt. Använd i så fall metoden XImage.Rename. |
| metadata | Metadata för bilden. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| save(stream) | Sparar bilddata till ström som JPEG-bild. |
| save(stream, format) | Sparar bilden till ström med önskat format. |
| save(stream, resolution) | Sparar bilddata i en ström som JPEG-bild med angiven upplösning. |
| save(stream, format, resolution) | Sparar bilden i en ström med begärt format och angiven upplösning. |
| rename(name) | Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet |
| get_color_type() | Returnerar bildens färgtyp. |
| detect_color_type(bmp) | Returnerar bildens färgtyp. |
| is_the_same_object(image) | Returnerar true om båda bilderna refererar till samma objekt. |
| get_name_in_collection() | Returnerar namn på bilden i ints-samlingen. |
| to_stream() | Returnerar den ursprungliga bildströmmen. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

