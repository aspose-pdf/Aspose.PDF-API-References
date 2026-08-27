---
title: "PdfXmpMetadata.Add"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Добавляет значение в XMP‑метаданные"
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Добавляет значение в XMP‑метаданные.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | DefaultMetadataProperties | Имя ключа. |
| значение | XmpValue | Значение, которое будет добавлено. |

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
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | PDF‑объект расширения, который нужно добавить. |
| namespacePrefix | String | Префикс схемы. |
| namespaceUri | String | URI пространства имён схемы. |
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
| ключ | String | Ключ нового элемента. |
| значение | XmpValue | Значение элемента. |

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
| ключ | String | Ключ нового элемента. |
| значение | Object | Значение элемента. |

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Добавляет пару ключ‑значение в словарь.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Элемент, который будет добавлен. |

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


