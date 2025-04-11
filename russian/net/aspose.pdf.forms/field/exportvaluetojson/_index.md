---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Метод поля. Экспортирует содержимое указанного поля в поток JSON. Значения полей кнопок не экспортируются
type: docs
weight: 180
url: /ru/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Метод Field.ExportValueToJson

Экспортирует содержимое указанного поля в поток JSON. Значения полей кнопок не экспортируются.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputJsonStream | Stream | Выходной поток JSON, в который будут записаны данные поля. |
| indented | Boolean | Необязательный. Указывает, должен ли выходной JSON быть отформатирован с отступами для лучшей читаемости. Значение по умолчанию - true. |

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### См. также

* класс [Field](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)