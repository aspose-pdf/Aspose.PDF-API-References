---
title: ImportFdf
second_title: Aspose.PDF для справочника API .NET
description: Импортирует содержимое полей из файла fdf и помещает их в новый pdf.
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Импортирует содержимое полей из файла fdf и помещает их в новый pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFdfStream | Stream | Входной поток fdf. |

### Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Смотрите также

* class [Form](../../form)
* пространство имен [Aspose.Pdf.Facades](../../form)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
