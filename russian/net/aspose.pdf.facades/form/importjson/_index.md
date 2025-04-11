---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Импортирует все данные полей из потока JSON в поля документа, сопоставляя поля по их полным именам
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/form/importjson/
---
## Метод Form.ImportJson

Импортирует все данные полей из потока JSON в поля документа, сопоставляя поля по их полным именам.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной поток JSON, содержащий данные полей, которые необходимо импортировать в поля документа. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)