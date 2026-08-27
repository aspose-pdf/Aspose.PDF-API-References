---
title: "PdfExtractor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass för att extrahera bilder och text från PDF‑dokument."
type: docs
weight: 210
url: /sv/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Klass för att extrahera bilder och text från PDF‑dokument.

Typen PdfExtractor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfExtractor() | Initierar ett nytt [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) objekt. |
| PdfExtractor(document) | Initierar en ny instans av klassen PdfExtractor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| start_page | Hämtar eller anger startsida i sidintervallet där extraheringsoperationen ska utföras. |
| end_page | Hämtar eller anger slutsida i sidintervallet där extraheringsoperationen ska utföras. |
| extract_text_mode | Ställer in läget för resultatet av textutdragning. |
| text_search_options | Hämtar eller anger alternativ för textsökning. |
| extract_image_mode | Ställer in läget för bildutdragningsprocessen. |
| is_bidi | Är sant när texten innehåller hebreiska eller arabiska tecken. Detta fall måste särskilt beaktas eftersom<br/>            strängfunktioner ändrar sitt beteende och startar textprocessen från höger till vänster (förutom siffror <br/>            och andra icke‑texttecken). |
| resolution | Ställer in eller hämtar upplösning för extraherade bilder.<br/>            Standardvärdet är 150.<br/>            Bilder med högre upplösningsvärde är tydligare.<br/>            Att öka upplösningsvärdet leder dock till längre tid och mer minne som behövs för att extrahera bilder.<br/>            Vanligtvis räcker det att sätta upplösningen till 150 eller 300 för att få en klar bild. |
| password | Hämtar eller anger lösenordet för inmatningsfilen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(input_file) | Koppla in inmatnings‑PDF‑fil. |
| bind_pdf(input_stream) | Binder PDF‑dokument från ström. |
| bind_pdf(src_doc) | Initierar fasaden. |
| extract_text() | Extraherar text från ett Pdf‑dokument med Unicode‑kodning. |
| extract_text(encoding) | Extraherar text från ett PDF-dokument med angiven kodning. |
| get_text(output_file) | Sparar text till fil. se även:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Sparar text till ström. se även:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Sparar text till ström. se även:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Hämtar nästa bild från PDF-dokumentet. Obs: ExtractImage måste anropas innan den här metoden används. |
| get_next_image(output_file, format) | Hämtar nästa bild från PDF-dokumentet med angivet bildformat. Obs: ExtractImage måste anropas innan den här metoden används. |
| get_next_image(output_stream, format) | Hämtar nästa bild från PDF-filen och lagrar den i en ström med angivet bildformat. |
| get_next_image(output_stream) | Hämtar nästa bild från PDF-filen och lagrar den i en ström med angivet bildformat. |
| extract_attachment() | Extraherar bilagor från ett PDF-dokument. |
| extract_attachment(attachment_file_name) | Extraherar bilaga till PDF-filen med bilagnamnet. |
| get_next_page_text(output_file) | Sparar en sidas text till fil. |
| get_next_page_text(output_stream) | Sparar en sidas text till ström. |
| close() | Avslutar Aspose.Pdf.Document som är bunden till en fasad. |
| extract_image() | Extraherar bilder från PDF-filen. |
| has_next_image() | Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Obs: ExtractImage måste anropas innan den här metoden används. |
| get_attach_names() | Returnerar en lista över bilagor i PDF-filen. Obs: ExtractAttachments måste anropas innan den här metoden används. |
| get_attachment(output_path) | Lagrar bilagan i en fil. |
| has_next_page_text() | Indikerar om fler texter kan hämtas eller inte. |
| get_attachment_info() | Hämtar listan över bilagor. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

