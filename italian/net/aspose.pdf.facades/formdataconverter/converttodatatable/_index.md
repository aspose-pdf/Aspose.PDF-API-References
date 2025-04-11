---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormDataConverter. Convertire file di flussi in tabella
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Metodo FormDataConverter.ConvertToDataTable

Convertire file di flussi in tabella.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStreams | Stream[] | Array di flussi sorgente nel formato specificato. |
| sourceType | DataType | Formato dei dati nei flussi. I valori validi sono: PDF, FDF, XFDF, XML. |

## Esempi

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

### Vedi anche

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)