---
title: "Font"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar teckensnittobjekt."
type: docs
weight: 100
url: /sv/python-net/aspose.pdf.text/font/
---

## Font class

Representerar teckensnittobjekt.

Font-typen exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| font_name | Hämtar teckensnittets namn för [Font](/pdf/python-net/aspose.pdf.text/font/)‑objektet. |
| decoded_font_name | Ibland kan PDF-teckensnitt (vanligtvis kinesiska/japanska/koreanska teckensnitt) ha ett specifikt teckensnittsnamn.<br/>            Detta namn är värdet för PDF-teckensnittsegenskapen "BaseFont" och ibland kan denna egenskap<br/>            representeras i hexadecimal form. Om man läser detta namn direkt kan det visas<br/>            i ett oläsbart format. För att få ett läsbart format är det nödvändigt att avkoda teckensnittets namn enligt<br/>            regler som är specifika för detta teckensnitt. <br/>            Denna egenskap returnerar avkodat teckensnittsnamn, så använd den i fall där du stöter<br/>            på ett oläsbart [font_name](/pdf/python-net/aspose.pdf.text/font/).<br/>            Om egenskapen [font_name](/pdf/python-net/aspose.pdf.text/font/) har ett läsbart format kommer denna egenskap att vara densamma som <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), så du kan använda denna egenskap i alla fall när du behöver<br/>            få teckensnittsnamnet i ett läsbart format. |
| base_font | Hämtar BaseFont‑värdet för PDF‑teckensnittobjektet. Även känt som PostScript‑namnet för teckensnittet. |
| is_embedded | Hämtar eller anger ett värde som indikerar om teckensnittet är inbäddat.<br/>            Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat |
| is_subset | Hämtar eller anger ett värde som indikerar om teckensnittet är en delmängd.<br/>             Teckensnitt baserat på IFont kommer automatiskt att bli delmängd och inbäddat |
| is_accessible | Hämtar indikation på om teckensnittet finns (är installerat) i systemet. |
| font_options | Användbara egenskaper för att finjustera teckensnittsbeteende |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_last_font_embedding_error() | Målet med denna metod är att returnera felbeskrivning om ett försök<br/>            att bädda in teckensnitt misslyckades. Om det inte finns några felreturneras en tom sträng. |
| save(stream) | Sparar teckensnittet i strömmen.<br/>            Observera att teckensnittet sparas i ett mellanliggande TTF-format som endast är avsett att användas i en konverterad kopia av det ursprungliga dokumentet.<br/>            Teckensnittsfilen är inte avsedd att användas utanför det ursprungliga dokumentets sammanhang. |
| measure_string(str, font_size) | Mäter strängen. |

### Se även

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

