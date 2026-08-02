---
title: "Field.ImportValueFromJson"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Field метод. Импортирует данные в указанные поля из JSON‑потока на основе точного соответствия полных имен полей."
type: docs
weight: 210
url: /ru/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Импортирует данные в указанные поля из потока JSON, основываясь на точном совпадении полных имён полей.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной JSON‑поток, содержащий данные поля для импорта в поле. |

### Возвращаемое значение

True, если поле найдено в JSON‑потоке; иначе — false

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

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Импортирует данные в указанное поле из потока JSON, используя полное имя, указанное в переменной 'fieldFullNameInJSON', для сопоставления.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputJsonStream | Stream | Входной JSON‑поток, содержащий данные поля для импорта в поле. |
| fieldFullNameInJSON | String | Имя данных в JSON‑потоке для сопоставления. Если данные в JSON‑потоке имеют вложенную структуру, полное имя следует указывать со всеми родительскими и дочерними элементами, разделёнными точкой '.' |

### Возвращаемое значение

True, если поле найдено в json‑файле; иначе — false

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

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


