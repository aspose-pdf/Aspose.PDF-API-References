---
title: "Field.ExportValueToJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Field. Экспортирует содержимое указанного поля в поток JSON. Значения полей кнопок не экспортируются."
type: docs
weight: 180
url: /ru/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

Экспортирует содержимое указанного поля в поток JSON. Значения полей‑кнопок не экспортируются.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputJsonStream | Stream | Поток JSON вывода, в который будут записаны данные поля. |
| с отступами | Boolean | Необязательно. Указывает, следует ли делать отступы в JSON‑выводе для лучшей читаемости. Значение по умолчанию — true. |

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### См. также

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


