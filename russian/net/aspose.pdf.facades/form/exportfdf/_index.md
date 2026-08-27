---
title: "Form.ExportFdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Экспортирует содержимое полей pdf в поток fdf"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


