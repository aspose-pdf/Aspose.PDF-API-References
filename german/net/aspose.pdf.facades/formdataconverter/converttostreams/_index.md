---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-Methode. Daten in Tabelle in Streams umwandeln
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams-Methode

Daten in Tabelle in Streams umwandeln.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destStream | Stream[] | Streams, in denen die Daten gespeichert werden. |
| destType | DataType | Typ der gespeicherten Daten. Gültige Werte sind: XML, FDF, XFDF. |

## Beispiele

```csharp
DataTable table = new DataTable();
table.Columns.Add("radiobuttonField");
table.Columns.Add("textField");
table.Columns.Add("checkboxField");
table.Columns.Add("listboxField");
table.Columns.Add("comboboxField");
DataRow newrow = table.NewRow();
newrow["textField"] = "NEW DATA";
newrow["listboxField"] = "Item1";
newrow["comboboxField"] = "Item1";
newrow["checkboxField"] = "true";
newrow["radiobuttonField"] = "true";
table.Rows.Add(newrow);
fc.Table = table;
fc.ConvertToStreams(new Stream[] { stream }, DataType.XML);
```

### Siehe auch

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)