---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Добавляет значение в XMP метаданные
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Добавляет значение в XMP метаданные.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | DefaultMetadataProperties | Имя ключа. |
| value | XmpValue | Значение, которое будет добавлено. |

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### См. также

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Добавляет поле расширения в метаданные.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | Объект расширения pdf для добавления. |
| namespacePrefix | String | Префикс схемы. |
| namespaceUri | String | URI пространства имен схемы. |
| schemaDescription | String | Необязательное описание схемы. |

### См. также

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Добавляет новый элемент в объект словаря.

```csharp
public void Add(string key, XmpValue value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ нового элемента. |
| value | XmpValue | Значение элемента. |

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Добавляет новый элемент в объект словаря.

```csharp
public void Add(string key, object value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ нового элемента. |
| value | Object | Значение элемента. |

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Добавляет пару с ключом и значением в словарь.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Элемент для добавления. |

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)