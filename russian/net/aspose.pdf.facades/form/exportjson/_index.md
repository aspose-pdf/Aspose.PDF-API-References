---
title: "Form.ExportJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Экспортирует содержимое всех полей документа в поток JSON. Значения полей‑кнопок не экспортируются."
type: docs
weight: 80
url: /ru/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Экспортирует содержимое всех полей документа в поток JSON. Значения полей кнопок не экспортируются.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputJsonStream | Stream | Выходной поток JSON, в который будут записаны данные полей документа. |
| с отступами | Boolean | Необязательно. Указывает, следует ли делать отступы в JSON‑выводе для лучшей читаемости. Значение по умолчанию — true. |

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


