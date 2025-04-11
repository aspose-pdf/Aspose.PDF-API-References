---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Метод WidgetAnnotation. Экспортирует указанный PDF-поле формы в формат JSON и записывает результат в предоставленный поток
type: docs
weight: 120
url: /ru/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Экспортирует указанное PDF-поле формы в формат JSON и записывает результат в предоставленный поток.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для записи JSON-выхода. |
| options | ExportFieldsToJsonOptions | Дополнительные настройки для экспорта поля формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для указанного поля формы и его дочерних элементов, если таковые имеются.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* класс [WidgetAnnotation](../)
* пространство имен [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Экспортирует указанное PDF-поле формы в формат JSON и записывает результат в указанный файл.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла для записи JSON-выхода. |
| options | ExportFieldsToJsonOptions | Дополнительные настройки для экспорта поля формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для указанного поля формы и его дочерних элементов, если таковые имеются.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* класс [WidgetAnnotation](../)
* пространство имен [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../../)