---
title: "PdfXmpMetadata.Remove"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Удаляет элемент с указанным ключом"
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Удаляет элемент с указанным ключом.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | DefaultMetadataProperties | Ключ элемента, который будет удалён. |

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### См. также

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Удаляет ключ из словаря.

```csharp
public bool Remove(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Ключ, который будет удалён. |

### Возвращаемое значение

True — если ключ удалён; иначе false.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Удаляет пару ключ/значение из коллекции.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Пара ключ/значение для удаления. |

### Возвращаемое значение

true, если пара была найдена и удалена.

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


