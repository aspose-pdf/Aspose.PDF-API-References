---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormDataConverter. Convertir des données dans un tableau en flux
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Méthode FormDataConverter.ConvertToStreams

Convertir des données dans un tableau en flux.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| destStream | Stream[] | Flux où les données seront stockées. |
| destType | DataType | Type de données stockées. Les valeurs valides sont : XML, FDF, XFDF. |

## Exemples

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

### Voir aussi

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)