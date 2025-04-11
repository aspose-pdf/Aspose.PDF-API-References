---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Импортирует содержимое полей из файла xfdfxml и помещает их в новый pdf
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/form/importxfdf/
---
## Метод Form.ImportXfdf

Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXfdfStream | Stream | Входной поток xfdf(xml). |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)