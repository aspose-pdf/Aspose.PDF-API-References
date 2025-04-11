---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 方法。向 XMP 元数据添加值
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

向 XMP 元数据添加值。

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | DefaultMetadataProperties | 键名称。 |
| value | XmpValue | 将要添加的值。 |

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### 另请参见

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

向元数据添加扩展字段。

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | 要添加的 pdf 扩展对象。 |
| namespacePrefix | String | 模式的前缀。 |
| namespaceUri | String | 模式的命名空间 URI。 |
| schemaDescription | String | 模式的可选描述。 |

### 另请参见

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

向字典对象添加新元素。

```csharp
public void Add(string key, XmpValue value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | String | 新元素的键。 |
| value | XmpValue | 元素的值。 |

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

向字典对象添加新元素。

```csharp
public void Add(string key, object value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | String | 新元素的键。 |
| value | Object | 元素的值。 |

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

向字典中添加键值对。

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 要添加的项。 |

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)