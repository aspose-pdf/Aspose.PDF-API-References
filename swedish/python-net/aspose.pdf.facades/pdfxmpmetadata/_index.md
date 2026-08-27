---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass för manipulation med XMP-metadata."
type: docs
weight: 380
url: /sv/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Klass för manipulation med XMP-metadata.

Typen PdfXmpMetadata exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfXmpMetadata() | Konstruktor för PdfXmpMetadata. |
| PdfXmpMetadata(document) | Initierar en ny instans av PdfXmpMetadata-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| nycklar | Hämtar nycklar från ordboken. |
| värden | Hämtar samlingen av värden i ordboken. |
| is_fixed_size | Returnerar true om samlingen har fast storlek. |
| is_synchronized | Returnerar true om samlingen är synkroniserad. |
| sync_root | Hämtar synkroniseringsobjektet för samlingen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| add(key, value) | Lägger till värde i XMP-metadata. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Lägger till ett extensionsfält i metadata. |
| add(key, value) | Lägger till ett nytt element i ordboksobjektet. |
| add(key, value) | Lägger till ett extensionsfält i metadata. |
| remove(key) | Tar bort element med angiven nyckel. |
| remove(key) | Tar bort nyckel från ordboken. |
| contains(key) | Kontrollerar om ordboken innehåller den angivna nyckeln. |
| contains(property) | Kontrollerar om ordboken innehåller den angivna egenskapen. |
| get_xmp_metadata() | Hämta XmpMetadata för den angivna pdf-filen i XML-format. |
| get_xmp_metadata(name) | Hämta en del av XmpMetadata för den inmatade pdf-filen enligt ett metanamn. |
| close() | Frigör alla resurser som är associerade med den aktuella fasaden. |
| register_namespace_uri(prefix, namespace_uri) | Registrerar namnrymdens URI. |
| get_namespace_uri_by_prefix(prefix) | Hämtar namnrymdens URI efter prefix. |
| get_prefix_by_namespace_uri(namespace_uri) | Hämtar prefixet efter namnrymdens URI. |
| contains_key(key) | Bestämmer om denna ordbok innehåller den angivna nyckeln. |
| try_get_value(key, value) | Försöker hitta nyckeln i ordboken och hämtar värdet om det hittas. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

