---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metodu. Akış dosyalarını tabloya dönüştür
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable metodu

Akış dosyalarını tabloya dönüştür.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceStreams | Stream[] | Belirtilen formatta kaynak akışların dizisi. |
| sourceType | DataType | Akışlardaki verilerin formatı. Geçerli değerler: PDF, FDF, XFDF, XML. |

## Örnekler

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

### Ayrıca Bakınız

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)