---
title: FormDataConverter.ConvertToDataTable
second_title: Aspose.PDF for .NET API Reference
description: Метод FormDataConverter. Преобразовать файлы потоков в таблицу
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/formdataconverter/converttodatatable/
---
## Метод FormDataConverter.ConvertToDataTable

Преобразовать файлы потоков в таблицу.

```csharp
public void ConvertToDataTable(Stream[] sourceStreams, DataType sourceType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceStreams | Stream[] | Массив исходных потоков в указанном формате. |
| sourceType | DataType | Формат данных в потоках. Допустимые значения: PDF, FDF, XFDF, XML. |

## Примеры

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

### См. также

* enum [DataType](../../datatype/)
* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)