---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary 属性。获取或设置具有指定键的元素
type: docs
weight: 60
url: /zh/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary 索引器

获取或设置具有指定键的元素。

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| key | 要获取或设置的元素的键。 |

### 返回值

具有指定键的元素。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 键为 null。 |
| KeyNotFoundException | 检索属性时未找到键。 |
| ArgumentException | 如果键无法编辑/设置则抛出异常。 |

### 另请参阅

* 接口 [ICosPdfPrimitive](../../icospdfprimitive/)
* 类 [CosPdfDictionary](../)
* 命名空间 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 程序集 [Aspose.PDF](../../../)