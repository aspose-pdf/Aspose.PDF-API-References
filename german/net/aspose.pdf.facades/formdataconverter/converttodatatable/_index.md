---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-Methode. Konvertieren Sie Dateien von Streams in eine Tabelle
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable-Methode

Konvertieren Sie Dateien von Streams in eine Tabelle.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreams | Stream[] | Array von Quellstreams im angegebenen Format. |
| sourceType | DataType | Format der Daten in Streams. Gültige Werte sind: PDF, FDF, XFDF, XML. |

## Beispiele

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
FormDataConverter fc = new FormDataConverter();
Stream stream = new FileStream("PdfWithAcroForm.pdf", FileMode.Open);
fc.Table = table;
fc.ConvertToDataTable(new Stream[] { stream }, DataType.PDF);
stream.Close();
```

### Siehe auch

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)