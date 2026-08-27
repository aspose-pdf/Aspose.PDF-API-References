---
title: "FormDataConverter"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att konvertera data från ett format till ett annat format.<br/>            Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB.<br/>            Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf.<br/>            Den kan konvertera fdf till xml med \\\"hard-named\\\"‑tagg."
type: docs
weight: 100
url: /sv/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Representerar en klass för att konvertera data från ett format till ett annat format.<br/>            Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB.<br/>            Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf.<br/>            Den kan konvertera fdf till xml med \"hard-named\"‑tagg.

Typen FormDataConverter visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| FormDataConverter() | Initierar en ny instans av klassen FormDataConverter |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| create_missing_field | ConvertToDataTable kommer att skapa obligatoriskt fält om det inte finns i tabellen. |
| replace_existing_table | ImportIntoDatabase kommer att ta bort befintlig tabell och skapa en ny tabell om denna egenskap är satt till true. |
| clear_table_before_export | ExportFromData kommer att rensa tabellen innan dataexport. |
| create_missing_table | ImportIntoDatabase kommer att skapa tabellen om den inte finns. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Konvertera XML-import/export-formulärdatafil till FDF-format. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Konvertera FDF-fil till XML. |
| convert_to_data_table(source_streams, source_type) | Konvertera filer av strömmar till en tabell. |
| import_into_data_base(connect_string, db_type) | Importerar data från tabell till databas. |
| export_from_data_base(connect_string, db_type) | Exporterar data från databas till tabell. |
| convert_to_streams(dest_stream, dest_type) | Konvertera data i tabell till strömmar. |
| conver_to_streams(dest_stream, dest_type) | Denna metod är föråldrad. Använd ConvertToStreams() istället. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

