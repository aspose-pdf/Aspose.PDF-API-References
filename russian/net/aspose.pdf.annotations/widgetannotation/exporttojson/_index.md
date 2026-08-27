---
title: "WidgetAnnotation.ExportToJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод WidgetAnnotation. Экспортирует указанный PDF‑поле формы в формат JSON и записывает результат в предоставленный поток."
type: docs
weight: 120
url: /ru/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Экспортирует указанное поле формы PDF в формат JSON и записывает результат в предоставленный поток.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который записывается JSON‑вывод. |
| options | ExportFieldsToJsonOptions | Необязательные настройки для экспорта поля формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для указанного поля формы и его дочерних элементов, если они присутствуют.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### См. также

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Экспортирует указанное поле формы PDF в формат JSON и записывает результат в указанный файл.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, в который будет записан вывод JSON. |
| options | ExportFieldsToJsonOptions | Необязательные настройки для экспорта поля формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для указанного поля формы и его дочерних элементов, если они присутствуют.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### См. также

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


