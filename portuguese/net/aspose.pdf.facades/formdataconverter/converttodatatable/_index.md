---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Converter arquivos de fluxos em tabela
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Método FormDataConverter.ConvertToDataTable

Converter arquivos de fluxos em tabela.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceStreams | Stream[] | Array de fluxos de origem no formato especificado. |
| sourceType | DataType | Formato dos dados nos fluxos. Os valores válidos são: PDF, FDF, XFDF, XML. |

## Exemplos

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

### Veja Também

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)