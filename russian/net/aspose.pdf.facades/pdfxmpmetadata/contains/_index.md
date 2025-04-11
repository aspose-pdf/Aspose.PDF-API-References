---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Проверяет, содержит ли словарь указанный ключ
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
| key | String | Ключ, который будет проверяться. |

### Возвращаемое значение

True - если словарь содержит указанный ключ; в противном случае false.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### См. также

* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Проверяет, содержит ли словарь указанное свойство.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| property | DefaultMetadataProperties | Свойство, которое будет проверяться. |

### Возвращаемое значение

True - если словарь содержит указанное свойство; в противном случае false.

### См. также

* перечисление [DefaultMetadataProperties](../../defaultmetadataproperties/)
* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Проверяет, содержится ли указанная пара ключ-значение в словаре.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Пара ключ-значение. |

### Возвращаемое значение

true, если эта пара была найдена.

### См. также

* класс [XmpValue](../../../aspose.pdf/xmpvalue/)
* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)