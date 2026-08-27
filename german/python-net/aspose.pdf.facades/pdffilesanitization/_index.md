---
title: "PdfFileSanitization"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Bereinigungs‑ und Wiederherstellungs‑API dar.<br/>            Verwenden Sie sie, wenn Sie Dokumente nicht auf andere Weise erstellen/öffnen können."
type: docs
weight: 290
url: /de/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Stellt eine Bereinigungs‑ und Wiederherstellungs‑API dar.<br/>            Verwenden Sie sie, wenn Sie Dokumente nicht auf andere Weise erstellen/öffnen können.

Der Typ PdfFileSanitization stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileSanitization() | Initialisiert eine neue Instanz der Klasse PdfFileSanitization |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| log | Nachdem die Datei gespeichert wurde, können Sie prüfen, was mit der Datei gemacht wurde. |
| use_trim_top | Ermöglicht das Entfernen von Daten vor den PDF-Daten. |
| use_trim_bottom | Ermöglicht das Entfernen von Daten nach den PDF-Daten |
| use_rebuild_xref_and_trailer | Ermöglicht das Erzeugen eines neuen Xref und Trailers für das Dokument. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(input_file) | Bindet eine PDF-Datei zum Bereinigen. |
| bind_pdf(input_stream) | Bindet einen PDF-Stream zum Bereinigen. |
| bind_pdf(src_doc) | Initialisiert die Fassade. |
| save(output_file) | Speichert das resultierende PDF in einer Datei. |
| save(output_stream) | Speichert das resultierende PDF in den Stream. |
| close() | Schließt die Fassade. |
| recover() | Stellt das Dokument wieder her.<br/>            Verwenden Sie Eigenschaften, um es anzupassen. |
| trim_top() | Entfernt Daten vor %PDF. |
| trim_bottom() | Entfernt Daten nach dem letzten %%EOF. |
| rebuild_xref_and_trailer() | Entfernt das alte xref mit Trailer und erstellt ein neues xref mit Trailer. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

