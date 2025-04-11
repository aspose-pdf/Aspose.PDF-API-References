---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Экспортирует содержимое полей pdf в поток fdf
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/form/exportfdf/
---
## Метод Form.ExportFdf

Экспортирует содержимое полей pdf в поток fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFdfStream | Stream | Выходной поток fdf. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)