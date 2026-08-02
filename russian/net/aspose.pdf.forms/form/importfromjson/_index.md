---
title: "Form.ImportFromJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Импортирует поля PDF‑формы из JSON‑формата, предоставленного в потоке"
type: docs
weight: 310
url: /ru/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Импортирует поля PDF‑формы из формата JSON, предоставленного в потоке.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, из которого читается JSON‑ввод. |

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

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Импортирует поля PDF‑формы из формата JSON, предоставленного в указанном файле.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла, из которого читается JSON‑ввод. |

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

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


