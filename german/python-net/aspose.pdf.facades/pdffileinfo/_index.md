---
title: "PdfFileInfo"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse zum Zugriff auf Metainformationen eines PDF‑Dokuments dar."
type: docs
weight: 270
url: /de/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Stellt eine Klasse zum Zugriff auf Metainformationen eines PDF‑Dokuments dar.

Der Typ PdfFileInfo stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfFileInfo() | Initialisiert eine neue Instanz der Klasse Aspose.Pdf.Facades.PdfFileInfo mit Standardwerten. |
| PdfFileInfo(input_stream) | Initialisiert eine neue Instanz der Klasse PdfFileInfo |
| PdfFileInfo(input_stream, password) | Initialisiert eine neue Instanz der Klasse PdfFileInfo |
| PdfFileInfo(input_file) | Initialisiert eine neue Instanz der Klasse PdfFileInfo |
| PdfFileInfo(input_file, password) | Initialisiert eine neue Instanz der Klasse PdfFileInfo |
| PdfFileInfo(document) | Initialisiert eine neue Instanz der Klasse PdfFileInfo |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| author | Liest oder setzt die Autor-Information des PDF-Dokuments. |
| is_encrypted | Überprüft, ob das PDF-Dokument verschlüsselt ist. |
| is_pdf_file | Überprüft, ob die Eingabequelle eine gültige PDF-Datei ist. |
| use_strict_validation | Verwendet strenge Validierungsregeln über die Verwendung der Eigenschaft [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Liest oder setzt die Erstellungsdatum-Information des PDF-Dokuments. |
| creator | Liest oder setzt die Ersteller-Information des PDF-Dokuments. |
| has_collection | Gibt true zurück, wenn die aktuelle Eingabedatei eine 'Portfolio'-Datei ist, die eine Sammlung von PDF-Dateien enthält. |
| input_file | Liest oder setzt die Eingabedatei. |
| input_stream | Liest oder setzt den Eingabestream. |
| keywords | Liest oder setzt die Keywords-Information des PDF-Dokuments. |
| mod_date | Liest oder setzt die ModDate-Datum-Information des PDF-Dokuments. |
| number_of_pages | Liest die Anzahl der Dokumentseiten. |
| producer | Liest die Producer-Information des PDF-Dokuments. |
| subject | Liest oder setzt die Subject-Information des PDF-Dokuments. |
| title | Liest oder setzt die Title-Information des PDF-Dokuments. |
| password_type | Gibt den Typ des Passworts zurück, der beim Erstellen einer PdfFileInfo-Instanz übergeben wurde. Siehe mögliche Werte in [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Beachten Sie, dass das PDF-Dokument sowohl mit dem Benutzer‑ (oder Öffnungs‑) Passwort als auch mit dem Eigentümer‑ (oder Berechtigungs‑, Bearbeitungs‑) Passwort geöffnet werden kann. |
| has_open_password | Gibt true zurück, wenn ein Passwort benötigt wird, um ein passwortgeschütztes PDF-Dokument zu öffnen. |
| has_edit_password | Gibt true zurück, wenn ein Passwort benötigt wird, um Berechtigungen oder die Sicherheitseigenschaft des Dokuments zu ändern.<br/>            Beachten Sie, dass diese Eigenschaft nur gelesen werden kann, wenn im Konstruktor von [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) ein gültiges Passwort angegeben wurde.<br/>            Falls PasswordType den Wert Inaccessible hat (bedeutet, dass ein ungültiges Passwort angegeben wurde), schlägt das Lesen dieser Eigenschaft mit [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/) fehl. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_doc) | Initialisiert die Fassade. |
| bind_pdf(src_file) | Initialisiert die Fassade. |
| bind_pdf(src_stream) | Initialisiert die Fassade. |
| save(dest_stream) | Speichert das aktualisierte PDF-Dokument in den angegebenen Stream. |
| save(dest_file) | Speichert das aktualisierte PDF-Dokument in die angegebene Datei. |
| save_new_info(output_stream) | Speichert das aktualisierte PDF-Dokument in den angegebenen Stream. |
| save_new_info(output_file) | Speichert das aktualisierte PDF-Dokument in die angegebene Datei. |
| close() | Deinitialisiert die Instanz. |
| clear_info() | Löscht alle Metainformationen des PDF-Dokuments. |
| get_document_privilege() | Ruft die Berechtigungseinstellungen des PDF-Dokuments ab. |
| get_meta_info(name) | Ruft benutzerdefinierte Informationen des PDF-Dokuments mit dem Eigenschaftsnamen ab. Wenn keine Eigenschaft mit dem Namen übereinstimmt, wird ein leerer String zurückgegeben. |
| get_page_height(page_num) | Ruft die Höhe der angegebenen Seite ab. |
| get_page_rotation(page_num) | Ruft die Drehung der angegebenen Seite ab. |
| get_page_width(page_num) | Ruft die Breite der angegebenen Seite ab. |
| get_page_x_offset(page_num) | Ruft den horizontalen Versatz des Anzeigebereichs der angegebenen Seite ab. |
| get_page_y_offset(page_num) | Ruft den vertikalen Versatz des Anzeigebereichs der angegebenen Seite ab. |
| get_pdf_version() | Ruft die Versionsinformationen des PDF-Dokuments ab. |
| set_meta_info(name, value) | Setzt benutzerdefinierte Informationen des PDF-Dokuments. |
| save_new_info_with_xmp(output_file_name) | Ändert die explizit angegebenen Eigenschaften durch Festlegen von Dateiinformationen, andere Eigenschaften bleiben unverändert. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

