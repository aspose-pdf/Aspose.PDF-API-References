---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Экспортирует поля формы PDF в формат JSON и записывает результат в предоставленный поток
type: docs
weight: 240
url: /ru/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Экспортирует поля формы PDF в формат JSON и записывает результат в предоставленный поток.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который будет записан JSON-вывод. |
| options | ExportFieldsToJsonOptions | Дополнительные настройки для экспорта полей формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для каждого поля формы.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Экспортирует поля формы PDF в формат JSON и записывает результат в указанный файл.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, в который будет записан JSON-вывод. |
| options | ExportFieldsToJsonOptions | Дополнительные настройки для экспорта полей формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для каждого поля формы.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)