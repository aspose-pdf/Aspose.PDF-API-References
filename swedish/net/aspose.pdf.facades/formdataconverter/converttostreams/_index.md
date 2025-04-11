---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-metod. Konvertera data i tabellen till strömmar
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams metod

Konvertera data i tabellen till strömmar.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destStream | Stream[] | Strömmar där data kommer att lagras. |
| destType | DataType | Typ av lagrad data. Giltiga värden är: XML, FDF, XFDF. |

## Exempel

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

### Se Även

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)