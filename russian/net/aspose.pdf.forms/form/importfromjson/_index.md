---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Импортирует поля формы PDF из формата JSON, предоставленного в потоке
type: docs
weight: 290
url: /ru/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Импортирует поля формы PDF из формата JSON, предоставленного в потоке.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для чтения входных данных JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции импорта для каждого поля формы.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Импортирует поля формы PDF из формата JSON, предоставленного в указанном файле.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла для чтения входных данных JSON. |

### Возвращаемое значение

Коллекция [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), указывающая результат операции импорта для каждого поля формы.

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### См. также

* класс [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)