---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormDataConverter. Convertir des fichiers de flux en table
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Méthode FormDataConverter.ConvertToDataTable

Convertir des fichiers de flux en table.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | Tableau de flux source dans le format spécifié. |
| sourceType | DataType | Format des données dans les flux. Les valeurs valides sont : PDF, FDF, XFDF, XML. |

## Exemples

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

### Voir aussi

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)