---
title: "PdfConverter"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att konvertera varje sida i en pdf-fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu.<br/>            Stödd innehåll i pdf-filer: bilder, formulär, kommentarer."
type: docs
weight: 200
url: /sv/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Representerar en klass för att konvertera varje sida i en pdf‑fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu.<br/>            Stödd innehåll i pdf‑filer: bilder, formulär, kommentarer.

PdfConverter-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfConverter() | Initierar ett nytt [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) objekt. |
| PdfConverter(document) | Initierar en ny instans av PdfConverter-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| coordinate_type | Hämtar eller anger sidans koordinattyp (Media/Crop-boxar). CropBox-värdet används som standard. |
| show_hidden_areas | Hämtar eller anger flagga som styr synligheten för dolda områden på sidan. |
| rendering_options | Hämtar eller anger renderingsalternativ. |
| form_presentation_mode | Hämtar eller anger formulärets presentationsläge. |
| resolution | Hämtar eller anger upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| start_page | Hämtar eller anger startposition som du vill konvertera. Minimalt värde är 1. |
| end_page | Hämtar eller anger slutposition som du vill konvertera. |
| password | Hämtar eller anger dokumentets OwnerPassword. |
| user_password | Hämtar eller anger dokumentets UserPassword. |
| page_count | Hämtar sidantalet. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(input_file) | Kopplar ett Pdf-dokument för konvertering. |
| bind_pdf(input_stream) | Kopplar en Pdf-ström för konvertering. |
| bind_pdf(src_doc) | Initierar fasaden. |
| save_as_tiff(output_file) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, compression_type) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, image_width, image_height) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, page_size) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, page_size, settings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, image_width, image_height, settings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_stream) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| save_as_tiff(output_stream, compression_type) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_stream, page_size) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| save_as_tiff(output_stream, page_size, settings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff(output_stream, image_width, image_height) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff(output_file, settings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_file, settings, converter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| save_as_tiff(output_stream, settings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff(output_stream, settings, converter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| save_as_tiff_class_f(output_file, page_size) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| save_as_tiff_class_f(output_stream, page_size) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| save_as_tiff_class_f(output_file) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| save_as_tiff_class_f(output_stream) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| get_next_image(output_file) | Sparar bilden till fil med standard bildformat - jpeg. |
| get_next_image(output_file, page_size) | Sparar bilden till fil med den angivna sidstorleken och standard bildformat - jpeg. |
| get_next_image(output_file, format) | Sparar bilden till fil med det angivna bildformatet. |
| get_next_image(output_file, page_size, format) | Sparar bilden till fil med angiven sidstorlek och bildformat. |
| get_next_image(output_stream) | Sparar bilden till ström med standard bildformat - jpeg. |
| get_next_image(output_stream, page_size) | Sparar bilden till ström med angiven sidstorlek. |
| get_next_image(output_stream, format) | Sparar bilden till ström med angivet bildformat. |
| get_next_image(output_stream, page_size, format) | Sparar bilden till ström med angiven sidstorlek. |
| get_next_image(output_file, format, image_width, image_height, quality) | Sparar bilden till fil med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Sparar bilden till ström med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_file, format, image_width, image_height, quality) | Sparar bilden till fil med det angivna bildformatet, bildstorleken och kvaliteten. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Sparar bilden till ström med det angivna bildformatet, storleken och kvaliteten. |
| get_next_image(output_file, format, image_width, image_height) | Sparar bilden till fil med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_stream, format, image_width, image_height) | Sparar bilden till ström med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_stream, format, quality) | Sparar bilden till ström med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_stream, page_size, format, quality) | Sparar bilden till ström med given sidstorlek, bildformat och kvalitet. |
| get_next_image(output_file, format, quality) | Sparar bilden till fil med det angivna bildformatet, dimensionerna och kvaliteten. |
| get_next_image(output_file, page_size, format, quality) | Sparar bilden till fil med given sidstorlek, bildformat och kvalitet. |
| close() | Stäng instansen av PdfConverter och frigör resurserna. |
| do_convert() | Utför några initiala arbetsuppgifter för att konvertera ett pdf-dokument till bilder. |
| has_next_image() | Anger om pdf-filen har fler bilder eller inte. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Ingen |
| merge_images_as_tiff(input_images_streams) | Slår samman en lista med tiff-strömmar till en tiff-ström med flera bildrutor. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

