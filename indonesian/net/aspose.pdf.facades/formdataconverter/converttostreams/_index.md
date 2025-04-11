---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Metode FormDataConverter. Mengonversi data dalam tabel menjadi aliran
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Metode FormDataConverter.ConvertToStreams

Mengonversi data dalam tabel menjadi aliran.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destStream | Stream[] | Aliran tempat data akan disimpan. |
| destType | DataType | Tipe data yang disimpan. Nilai yang valid adalah: XML, FDF, XFDF. |

## Contoh

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

### Lihat Juga

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)