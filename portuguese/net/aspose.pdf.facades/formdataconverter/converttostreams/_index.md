---
title: FormDataConverter.ConvertToStreams
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Converter dados em tabela em streams
type: docs
weight: 90
url: /pt/net/aspose.pdf.facades/formdataconverter/converttostreams/
---
## Método FormDataConverter.ConvertToStreams

Converter dados em tabela em streams.

```csharp
public void ConvertToStreams(Stream[] destStream, DataType destType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destStream | Stream[] | Streams onde os dados serão armazenados. |
| destType | DataType | Tipo de dados armazenados. Valores válidos são: XML, FDF, XFDF. |

## Exemplos

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

### Veja Também

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)