---
title: Contains
second_title: Aspose.PDF for .NET API 参考
description: 检查字典是否包含指定的键
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

检查字典是否包含指定的键。

```csharp
public bool Contains(string key)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | String | 将被检查的键。 |

### 返回值

True - 如果字典包含指定的键；否则为假。

### 例子

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 也可以看看

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* 命名空间 [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* 部件 [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

检查字典是否包含指定的属性。

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| property | DefaultMetadataProperties | 将被检查的属性。 |

### 返回值

True - 如果字典包含指定的属性；否则为假。

### 也可以看看

* enum [DefaultMetadataProperties](../../defaultmetadataproperties)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* 命名空间 [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* 部件 [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

检查指定的键值对是否包含在字典中。

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 键值对。 |

### 返回值

如果这个 pauir 被发现，则为真。

### 也可以看看

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* 命名空间 [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->