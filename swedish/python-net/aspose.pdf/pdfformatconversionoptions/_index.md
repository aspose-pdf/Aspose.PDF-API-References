---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "representerar en uppsättning alternativ för att konvertera PDF-dokument"
type: docs
weight: 1220
url: /sv/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

representerar en uppsättning alternativ för att konvertera PDF-dokument

Typen PdfFormatConversionOptions exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Initierar en ny instans av klassen PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Initierar en ny instans av klassen PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Initierar en ny instans av klassen PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Initierar en ny instans av klassen PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Initierar en ny instans av klassen PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Initierar en ny instans av klassen PdfFormatConversionOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| is_async_image_streams_conversion_mode | Hämtar/sätter körning av bildströmmar i asynkront läge. |
| is_low_memory_mode | Är lågminneskonverteringsläge aktiverat |
| format | PDF-format. |
| log_file_name | Sökväg till fil där kommentarer kommer att lagras. |
| log_stream | Ström där kommentarer kommer att lagras. |
| error_action | Åtgärd för objekt som inte kan konverteras |
| transparency_action | Åtgärd för bildmaskerade objekt |
| convert_soft_mask_action | Åtgärd för bilder med mjuk mask. |
| default | Hämtar PdfFormatConversionOptions-objektet med standardparametrar |
| non_specification_cases | Innehåller flaggor för att styra PDF/A-konverteringsprocessen för fall då källdokumentet<br/>            inte motsvarar PDF/A-specifikationen. |
| symbolic_font_encoding_strategy | Strategi för att kopiera kodningsdata för symboliska teckensnitt om det symboliska TrueType-teckensnittet<br/>            har mer än en kodningstabell. |
| align_text | Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonverteringen <br/>            inte textjusteringen och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution<br/>            orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är aktiverad<br/>            utförs speciella justeringsoperationer. Flaggan bör endast sättas för dokument<br/>            som har problem med överlappande text eller extra mellanslag, eftersom användning av denna flagga minskar<br/>            prestanda och i vissa fall kan korrupta textinnehållet. |
| pua_text_processing_strategy | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| optimize_file_size | Hämtar eller anger en flagga som aktiverar/inaktiverar ett specialkonverteringsläge för att få ett PDF/A-dokument med minskad filstorlek.<br/>            Nu påverkar denna flagga optimeringen av teckensnitt som används i PDF-dokumentet, och möjligen kommer den i framtiden <br/>            även att användas för att slå på optimering av andra datastrukturer, såsom grafik.  <br/>            Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den<br/>            avsevärt minska konverteringsprestandan. |
| exclude_fonts_strategy | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. <br/>            Denna parameter är endast meningsfull när flaggan [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) är satt till true.<br/>            Som standard används en kombination av strategierna [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) och<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/). |
| font_embedding_options | Alternativ för fall då det inte är möjligt att bädda in vissa teckensnitt i PDF-dokumentet. |
| unicode_processing_rules | Regler för att lösa problem med Unicode-mappning. Kan vara null. |
| icc_profile_file_name | Hämtar eller anger filnamnet för ICC-profilen. Om null används standard-ICC-profilen. |
| not_accessible_fonts | Denna egenskap är en ut-egenskap. Den innehåller alla teckensnitt (teckensnittsnamn) som inte hittades på datorn <br/>            vid den senaste PDF/A-konverteringen. |
| is_transfer_info | Hämtar eller anger om data ska överföras från Info till Metadata vid konvertering till PDF 2.0. True som standard. |
| align_strategy | Strategi för att justera text. Denna parameter är endast meningsfull när flaggan [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) är satt till true. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

