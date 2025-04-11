---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Экспортирует содержимое полей pdf в xml поток. Значение полей кнопок не будет экспортировано
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/form/exportxfdf/
---
## Метод Form.ExportXfdf

Экспортирует содержимое полей pdf в xml поток. Значение поля кнопки не будет экспортировано.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXfdfStream | Stream | Выходной xml поток. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)