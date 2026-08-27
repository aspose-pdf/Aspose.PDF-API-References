---
title: "FormDataConverter"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die Daten von einem Format in ein anderes konvertiert.<br/>            Sie kann Daten in fdf/xml/pdf/xfdf in OLEDB/OdbcDB konvertieren.<br/>            Sie kann auch Daten in OLEDB/OdbcDB in fdf/xml/xfdf konvertieren.<br/>            Sie kann fdf in xml mit dem \\\"hard-named\\\"‑Tag konvertieren."
type: docs
weight: 100
url: /de/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Stellt eine Klasse dar, die Daten von einem Format in ein anderes konvertiert.<br/>            Sie kann Daten in fdf/xml/pdf/xfdf in OLEDB/OdbcDB konvertieren.<br/>            Sie kann auch Daten in OLEDB/OdbcDB in fdf/xml/xfdf konvertieren.<br/>            Sie kann fdf in xml mit dem \"hard-named\"‑Tag konvertieren.

Der Typ FormDataConverter stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| FormDataConverter() | Initialisiert eine neue Instanz der Klasse FormDataConverter |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| create_missing_field | ConvertToDataTable erstellt das erforderliche Feld, wenn es in der Tabelle nicht existiert. |
| replace_existing_table | ImportIntoDatabase wird die vorhandene Tabelle löschen und eine neue Tabelle erstellen, wenn diese Eigenschaft auf true gesetzt ist. |
| clear_table_before_export | ExportFromData wird die Tabelle vor dem Datenexport leeren. |
| create_missing_table | ImportIntoDatabase wird die Tabelle erstellen, wenn sie nicht existiert. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Konvertiere XML-Import/Export-Formulardatei in das FDF-Format. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Konvertiere FDF-Datei in XML. |
| convert_to_data_table(source_streams, source_type) | Konvertiere Dateien von Streams in eine Tabelle. |
| import_into_data_base(connect_string, db_type) | Importiert Daten von der Tabelle in die Datenbank. |
| export_from_data_base(connect_string, db_type) | Exportiert Daten von der Datenbank in die Tabelle. |
| convert_to_streams(dest_stream, dest_type) | Konvertiere Daten in der Tabelle in Streams. |
| conver_to_streams(dest_stream, dest_type) | Diese Methode ist veraltet. Bitte verwenden Sie ConvertToStreams() stattdessen. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

