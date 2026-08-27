---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Menge von Optionen zum Konvertieren von PDF-Dokumenten dar"
type: docs
weight: 1220
url: /de/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

Stellt eine Menge von Optionen zum Konvertieren von PDF-Dokumenten dar

Der Typ PdfFormatConversionOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Initialisiert eine neue Instanz der Klasse PdfFormatConversionOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| is_async_image_streams_conversion_mode | Liest/Schreibt den Durchlauf von Bildströmen im asynchronen Modus. |
| is_low_memory_mode | Ist der Low-Memory-Konvertierungsmodus aktiviert |
| format | PDF-Format. |
| log_file_name | Pfad zur Datei, in der Kommentare gespeichert werden. |
| log_stream | Strom, in dem Kommentare gespeichert werden. |
| error_action | Aktion für Objekte, die nicht konvertiert werden können |
| transparency_action | Aktion für maskierte Bildobjekte |
| convert_soft_mask_action | Aktion für Bilder mit Soft-Maske. |
| Standard | Liest das PdfFormatConversionOptions-Objekt mit Standardparametern |
| non_specification_cases | Enthält Flags zur Steuerung des PDF/A-Konvertierungsprozesses für Fälle, in denen das Quelldokument<br/>            nicht der PDF/A-Spezifikation entspricht. |
| symbolic_font_encoding_strategy | Strategie zum Kopieren von Kodierungsdaten für symbolische Schriften, wenn die symbolische TrueType-Schrift<br/>            mehr als eine Kodierungstabelle enthält. |
| align_text | Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig beeinflusst die Dokumentkonvertierung <br/>            die Textausrichtung nicht und lässt den Text unverändert. In einigen Fällen führt die Schriftartsubstitution<br/>            jedoch zu überlappendem Text oder zusätzlichen Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist,<br/>            werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden,<br/>            die Probleme mit überlappendem Text oder zusätzlichen Leerzeichen haben, da die Verwendung dieses Flags die<br/>            Leistung verringert und in einigen Fällen den Textinhalt beschädigen könnte. |
| pua_text_processing_strategy | Strategie zur Verarbeitung von Symbolen aus dem Unicode Private Use Area (PUA). |
| optimize_file_size | Liest oder setzt ein Flag, das den speziellen Konvertierungsmodus zum Erzeugen eines PDF/A-Dokuments mit reduzierter Dateigröße aktiviert/deaktiviert.<br/>            Dieses Flag wirkt sich jetzt auf die Optimierung der im PDF-Dokument verwendeten Schriften aus und könnte künftig auch<br/>            dazu verwendet werden, die Optimierung für andere Datenstrukturen, wie Grafiken, zu aktivieren.  <br/>            Die Kombination aus diesem Flag und dem Modus kann die Dateigröße erheblich reduzieren, gleichzeitig kann sie<br/>            die Konvertierungsleistung deutlich verringern. |
| exclude_fonts_strategy | Strategie(n) zum Ausschließen überflüssiger Schriften und zur Reduzierung der Dokumentdateigröße. <br/>            Dieser Parameter ist nur sinnvoll, wenn das Flag [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) auf true gesetzt ist.<br/>            Standardmäßig wird die Kombination der Strategien [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) und<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) verwendet. |
| font_embedding_options | Optionen für Fälle, in denen es nicht möglich ist, einige Schriften in ein PDF-Dokument einzubetten. |
| unicode_processing_rules | Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein. |
| icc_profile_file_name | Liest oder setzt den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet. |
| not_accessible_fonts | Diese Eigenschaft ist eine Out-Property. Sie enthält alle Schriften (Schriftnamen), die auf dem Computer <br/>            bei der letzten PDF/A-Konvertierung nicht gefunden wurden. |
| is_transfer_info | Liest oder setzt, ob Daten von Info zu Metadata beim Konvertieren zu PDF 2.0 übertragen werden sollen. Standardmäßig true. |
| align_strategy | Strategie zur Textausrichtung. Dieser Parameter ist nur sinnvoll, wenn das Flag [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) auf true gesetzt ist. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

