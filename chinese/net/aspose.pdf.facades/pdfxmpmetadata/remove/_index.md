---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 方法。删除具有指定键的元素"
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

移除具有指定键的元素。

```csharp
public void Remove(DefaultMetadataProperties key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | DefaultMetadataProperties | 将被删除的元素的键。 |

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### 另请参见

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

从字典中移除键。

```csharp
public bool Remove(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | String | 将被移除的键。 |

### 返回值

如果键已移除则为 True；否则为 false。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

从集合中移除键/值对。

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 要删除的键/值对。 |

### 返回值

如果找到并删除该对则为 true。

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


