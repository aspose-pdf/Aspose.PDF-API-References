---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Удаляет элемент с указанным ключом
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
| key | DefaultMetadataProperties | Ключ элемента, который будет удален. |

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
| key | String | Ключ, который будет удален. |

### Возвращаемое значение

True - если ключ удален; в противном случае - false.

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
| item | KeyValuePair`2 | Пара ключ/значение, которая будет удалена. |

### Возвращаемое значение

true, если пара была найдена и удалена.

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)