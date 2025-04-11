---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormDataConverter-Klasse. Stellt eine Klasse dar, um Daten von einem Format in ein anderes Format zu konvertieren. Sie kann die Daten in fdf/xml/pdf/xfdf in OLEDB/OdbcDB konvertieren. Sie kann auch die Daten in OLEDB/OdbcDB in die Daten in fdf/xml/xfdf konvertieren. Sie kann das fdf in das xml mit "hard-named" Tag konvertieren.
type: docs
weight: 4320
url: /de/net/aspose.pdf.facades/formdataconverter/
---
## Klasse FormDataConverter

Stellt eine Klasse dar, um Daten von einem Format in ein anderes Format zu konvertieren. Sie kann die Daten in fdf/xml/pdf/xfdf in OLEDB/OdbcDB konvertieren. Sie kann auch die Daten in OLEDB/OdbcDB in die Daten in fdf/xml/xfdf konvertieren. Sie kann das fdf in das xml mit "hard-named" Tag konvertieren.

```csharp
public sealed class FormDataConverter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData wird die Tabelle vor dem Datenexport leeren. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable erstellt das erforderliche Feld, wenn es nicht in der Tabelle vorhanden ist. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase erstellt die Tabelle, wenn sie nicht vorhanden ist. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase löscht die vorhandene Tabelle und erstellt eine neue Tabelle, wenn diese Eigenschaft auf true gesetzt ist. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Ruft den mittleren Datencontainer, eine DataTable, ab oder setzt ihn. Er muss definiert werden, bevor Daten von einem Format in ein anderes Format konvertiert werden. Die Spalten und der Tabellenname der DataTable sollten definiert werden. Der Tabellenname ist der Name der Tabelle in der Datenbank. Jeder Spaltenname ist der qualifizierte Feldname des PDFs. Jede Spaltenüberschrift ist der Spaltenname der Tabelle in der Datenbank. Wenn der Feldname mit dem Tabellenspaltennamen übereinstimmt, muss die Überschrift nicht angegeben werden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Diese Methode ist veraltet. Bitte verwenden Sie stattdessen ConvertToStreams(). |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Konvertiert Dateien von Streams in eine Tabelle. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Konvertiert Daten in der Tabelle in Streams. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exportiert Daten aus der Datenbank in die Tabelle. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importiert Daten aus der Tabelle in die Datenbank. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Konvertiert FDF-Datei in XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Konvertiert XML-Import-/Export-Formulardaten in FDF-Format. |

### Siehe auch

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)