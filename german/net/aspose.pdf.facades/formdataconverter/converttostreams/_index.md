---
title: ConvertToStreams
second_title: Aspose.PDF für .NET-API-Referenz
description: Daten in der Tabelle in Streams konvertieren.
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams method

Daten in der Tabelle in Streams konvertieren.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destStream | Stream[] | Streams, in denen Daten gespeichert werden. |
| destType | DataType | Art der gespeicherten Daten. Gültige Werte sind: XML, FDF, XFDF. |

### Beispiele

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

* enum [DataType](../../datatype)
* class [FormDataConverter](../../formdataconverter)
* namensraum [Aspose.Pdf.Facades](../../formdataconverter)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
