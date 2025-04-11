---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Convertir datos en tabla en flujos
type: docs
weight: 90
url: /es/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Método FormDataConverter.ConvertToStreams

Convertir datos en tabla en flujos.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destStream | Stream[] | Flujos donde se almacenarán los datos. |
| destType | DataType | Tipo de datos almacenados. Los valores válidos son: XML, FDF, XFDF. |

## Ejemplos

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

### Ver También

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)