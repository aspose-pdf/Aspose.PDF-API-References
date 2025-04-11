---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Metode FormDataConverter. Mengonversi file aliran menjadi tabel
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Metode FormDataConverter.ConvertToDataTable

Mengonversi file aliran menjadi tabel.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceStreams | Stream[] | Array aliran sumber dalam format yang ditentukan. |
| sourceType | DataType | Format data dalam aliran. Nilai yang valid adalah: PDF, FDF, XFDF, XML. |

## Contoh

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

### Lihat Juga

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)