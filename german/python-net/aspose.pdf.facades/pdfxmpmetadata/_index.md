---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse zur Manipulation von XMP-Metadaten."
type: docs
weight: 380
url: /de/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Klasse zur Manipulation von XMP-Metadaten.

Der Typ PdfXmpMetadata stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfXmpMetadata() | Konstruktor für PdfXmpMetadata. |
| PdfXmpMetadata(document) | Initialisiert eine neue Instanz der Klasse PdfXmpMetadata |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| Schlüssel | Liefert Schlüssel aus dem Wörterbuch. |
| Werte | Liefert die Sammlung von Werten im Wörterbuch. |
| is_fixed_size | Gibt true zurück, wenn die Sammlung feste Größe hat. |
| is_synchronized | Gibt true zurück, wenn die Sammlung synchronisiert ist. |
| sync_root | Liefert das Synchronisationsobjekt der Sammlung. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| add(key, value) | Fügt einen Wert zu XMP-Metadaten hinzu. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Fügt ein Erweiterungsfeld zu den Metadaten hinzu. |
| add(key, value) | Fügt ein neues Element zum Wörterbuchobjekt hinzu. |
| add(key, value) | Fügt ein Erweiterungsfeld zu den Metadaten hinzu. |
| remove(key) | Entfernt das Element mit dem angegebenen Schlüssel. |
| remove(key) | Entfernt den Schlüssel aus dem Wörterbuch. |
| contains(key) | Prüft, ob das Wörterbuch den angegebenen Schlüssel enthält. |
| contains(property) | Prüft, ob das Wörterbuch die angegebene Eigenschaft enthält. |
| get_xmp_metadata() | Liefert die XmpMetadata der Eingabe‑PDF im XML-Format. |
| get_xmp_metadata(name) | Rufen Sie einen Teil der XmpMetadata der Eingabepdf gemäß einem Metanamen ab. |
| close() | Gibt alle mit der aktuellen Fassade verbundenen Ressourcen frei. |
| register_namespace_uri(prefix, namespace_uri) | Registriert den Namespace-URI. |
| get_namespace_uri_by_prefix(prefix) | Ermittelt den Namespace-URI anhand des Präfixes. |
| get_prefix_by_namespace_uri(namespace_uri) | Ermittelt das Präfix anhand des Namespace-URI. |
| contains_key(key) | Bestimmt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| try_get_value(key, value) | Versucht, den Schlüssel im Wörterbuch zu finden und gibt den Wert zurück, falls gefunden. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

