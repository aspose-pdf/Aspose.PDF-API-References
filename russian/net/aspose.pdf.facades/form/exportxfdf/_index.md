---
title: "Form.ExportXfdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Экспортирует содержимое полей pdf в xml‑поток. Значения полей кнопок не будут экспортированы"
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXfdfStream | Stream | Выходной XML‑поток. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


