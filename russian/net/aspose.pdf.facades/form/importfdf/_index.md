---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Импортирует содержимое полей из файла fdf и помещает их в новый pdf
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/form/importfdf/
---
## Метод Form.ImportFdf

Импортирует содержимое полей из файла fdf и помещает их в новый pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFdfStream | Stream | Входной поток fdf. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)