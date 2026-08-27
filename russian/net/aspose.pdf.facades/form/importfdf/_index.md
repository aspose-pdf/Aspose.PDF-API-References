---
title: "Form.ImportFdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Импортирует содержимое полей из fdf‑файла и помещает его в новый pdf."
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Импортирует содержимое полей из файла fdf и помещает их в новый pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFdfStream | Stream | Входной fdf‑поток. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


