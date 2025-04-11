---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metodu. Tablo verilerini akışlara dönüştür
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## FormDataConverter.ConvertToStreams metodu

Tablo verilerini akışlara dönüştür.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destStream | Stream[] | Verilerin saklanacağı akışlar. |
| destType | DataType | Saklanan verinin türü. Geçerli değerler: XML, FDF, XFDF. |

## Örnekler

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

### Ayrıca Bakınız

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)