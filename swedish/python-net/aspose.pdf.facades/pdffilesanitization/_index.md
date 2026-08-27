---
title: "PdfFileSanitization"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar sanerings‑ och återställnings‑API.<br/>            Använd den om du inte kan skapa/öppna dokument på något annat sätt."
type: docs
weight: 290
url: /sv/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Representerar sanerings‑ och återställnings‑API.<br/>            Använd den om du inte kan skapa/öppna dokument på något annat sätt.

Typen PdfFileSanitization visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFileSanitization() | Initierar en ny instans av klassen PdfFileSanitization |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| log | Efter att filen har sparats kan du kontrollera vad som gjordes med filen. |
| use_trim_top | Tillåter att ta bort data före pdf-data. |
| use_trim_bottom | Tillåter att ta bort data efter pdf-data |
| use_rebuild_xref_and_trailer | Tillåter att generera ny xref och trailer för dokumentet. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(input_file) | Kopplar en Pdf-fil för sanering. |
| bind_pdf(input_stream) | Kopplar en Pdf-ström för sanering. |
| bind_pdf(src_doc) | Initierar fasaden. |
| save(output_file) | Sparar resultat-PDF till fil. |
| save(output_stream) | Sparar resultat-PDF till ström. |
| close() | Stänger fasaden. |
| recover() | Återställer dokument.<br/>            Använd egenskaper för att anpassa. |
| trim_top() | Tar bort data före %PDF. |
| trim_bottom() | Tar bort data efter sista %%EOF. |
| rebuild_xref_and_trailer() | Tar bort gammal xref med trailer och skapar en ny xref med trailer. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

