---
title: ConvertToDataTable
second_title: Referencia de API de Aspose.PDF para .NET
description: Convierte archivos de secuencias en tablas.
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## FormDataConverter.ConvertToDataTable method

Convierte archivos de secuencias en tablas.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceStreams | Stream[] | Matriz de secuencias de origen en formato especificado. |
| sourceType | DataType | Formato de datos en flujos. Los valores válidos son: PDF, FDF, XFDF, XML. |

### Ejemplos

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

### Ver también

* enum [DataType](../../datatype)
* class [FormDataConverter](../../formdataconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../formdataconverter)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
