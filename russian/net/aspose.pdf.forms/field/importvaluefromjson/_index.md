---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Метод поля. Импортирует данные в указанные поля из потока JSON на основе точного совпадения полных имен полей
type: docs
weight: 210
url: /ru/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Импортирует данные в указанные поля из потока JSON на основе точного совпадения полных имен полей.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной поток JSON, содержащий данные поля, которые необходимо импортировать в поле. |

### Возвращаемое значение

True, если поле было найдено в потоке JSON; в противном случае - false

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### См. также

* класс [Field](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Импортирует данные в указанное поле из потока JSON, используя полное имя, указанное в переменной 'fieldFullNameInJSON' для сопоставления.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной поток JSON, содержащий данные поля, которые необходимо импортировать в поле. |
| fieldFullNameInJSON | String | Имя данных в потоке JSON для сопоставления. Если данные в потоке JSON имеют вложенную структуру, полное имя должно быть указано со всеми родительскими и дочерними элементами, разделенными '.' |

### Возвращаемое значение

True, если поле было найдено в файле json; в противном случае - false

## Примеры

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### См. также

* класс [Field](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)