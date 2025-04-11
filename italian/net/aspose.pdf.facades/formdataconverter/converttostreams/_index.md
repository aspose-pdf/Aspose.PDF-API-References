---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormDataConverter. Converti i dati nella tabella in flussi
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Metodo FormDataConverter.ConvertToStreams

Converti i dati nella tabella in flussi.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destStream | Stream[] | Flussi in cui i dati saranno memorizzati. |
| destType | DataType | Tipo di dati memorizzati. I valori validi sono: XML, FDF, XFDF. |

## Esempi

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

### Vedi anche

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)