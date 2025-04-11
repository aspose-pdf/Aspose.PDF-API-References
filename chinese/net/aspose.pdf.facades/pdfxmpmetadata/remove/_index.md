---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 方法。删除具有指定键的元素
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

删除具有指定键的元素。

```csharp
public void Remove(DefaultMetadataProperties key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | DefaultMetadataProperties | 将被删除的元素的键。 |

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### 另请参阅

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

从字典中删除键。

```csharp
public bool Remove(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | String | 将被移除的键。 |

### 返回值

True - 如果键被移除；否则，false。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### 另请参阅

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

从集合中删除键/值对。

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 要删除的键/值对。 |

### 返回值

如果找到并删除了对，则为true。

### 另请参阅

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)