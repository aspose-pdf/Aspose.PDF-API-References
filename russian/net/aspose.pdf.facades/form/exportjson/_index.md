---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Экспортирует содержимое всех полей в документе в поток JSON. Значения полей кнопок не экспортируются
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/form/exportjson/
---
## Метод Form.ExportJson

Экспортирует содержимое всех полей в документе в поток JSON. Значения полей кнопок не экспортируются.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputJsonStream | Stream | Выходной поток JSON, в который будут записаны данные полей документа. |
| indented | Boolean | Необязательный. Указывает, должен ли выходной JSON быть отформатирован с отступами для лучшей читаемости. Значение по умолчанию - true. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)