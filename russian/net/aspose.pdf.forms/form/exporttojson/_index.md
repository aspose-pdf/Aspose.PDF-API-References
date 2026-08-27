---
title: "Form.ExportToJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Экспортирует поля PDF‑формы в JSON‑формат и записывает результат в предоставленный поток"
type: docs
weight: 260
url: /ru/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Экспортирует поля PDF‑формы в формат JSON и записывает результат в предоставленный поток.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который записывается JSON‑вывод. |
| options | ExportFieldsToJsonOptions | Необязательные параметры для экспорта полей формы в JSON. |

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

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Экспортирует поля PDF‑формы в формат JSON и записывает результат в указанный файл.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, в который будет записан вывод JSON. |
| options | ExportFieldsToJsonOptions | Необязательные параметры для экспорта полей формы в JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции экспорта для каждого поля формы.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### См. также

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


