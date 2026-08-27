---
title: "DictionaryEditor.Item"
second_title: "Aspose.PDF for .NET API 参考"
description: "DictionaryEditor 属性。获取或设置具有指定键的元素。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor indexer

获取或设置具有指定键的元素。

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 键 | 要获取或设置的元素的键。 |

### 返回值

具有指定键的元素。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 键为 null。 |
| KeyNotFoundException | 检索属性时未找到键。 |
| ArgumentException | 如果键无法编辑/设置则抛出异常。 |

### 另请参见

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


