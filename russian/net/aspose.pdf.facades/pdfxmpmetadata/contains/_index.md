---
title: "PdfXmpMetadata.Contains"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Проверяет, содержит ли словарь указанный ключ."
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Проверяет, содержит ли словарь указанный ключ.

```csharp
public bool Contains(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Ключ, который будет проверен. |

### Возвращаемое значение

True — если словарь содержит указанный ключ; иначе false.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Проверяет, содержит ли словарь указанное свойство.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | DefaultMetadataProperties | Свойство, которое будет проверено. |

### Возвращаемое значение

True — если словарь содержит указанное свойство; иначе false.

### См. также

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Проверяет, содержится ли указанная пара ключ‑значение в словаре.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Пара ключ‑значение. |

### Возвращаемое значение

true если эта пара найдена.

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


