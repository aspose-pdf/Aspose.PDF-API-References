---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfXmpMetadata 方法。检查字典是否包含指定的键。"
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
| 键 | String | 将要检查的键。 |

### 返回值

如果字典包含指定的键，则为 True；否则为 false。

## 示例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 另请参见

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

检查字典是否包含指定的属性。

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | DefaultMetadataProperties | 将要检查的属性。 |

### 返回值

如果字典包含指定的属性，则为 True；否则为 false。

### 另请参见

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

检查字典中是否包含指定的键值对。

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 键值对。 |

### 返回值

如果找到此键值对，则为 true。

### 另请参见

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


