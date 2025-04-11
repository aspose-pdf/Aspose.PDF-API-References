---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 方法。检查字典是否包含指定的键
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

检查字典是否包含指定的键。

```csharp
public bool Contains(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | 字符串 | 将被检查的键。 |

### 返回值

如果字典包含指定的键，则为真；否则为假。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 另请参见

* 类 [PdfXmpMetadata](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

检查字典是否包含指定的属性。

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | DefaultMetadataProperties | 将被检查的属性。 |

### 返回值

如果字典包含指定的属性，则为真；否则为假。

### 另请参见

* 枚举 [DefaultMetadataProperties](../../defaultmetadataproperties/)
* 类 [PdfXmpMetadata](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

检查指定的键值对是否包含在字典中。

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 键值对。 |

### 返回值

如果找到该对，则为真。

### 另请参见

* 类 [XmpValue](../../../aspose.pdf/xmpvalue/)
* 类 [PdfXmpMetadata](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)