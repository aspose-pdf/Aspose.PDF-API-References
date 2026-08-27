---
title: "DictionaryEditor.Remove"
second_title: "Aspose.PDF for .NET API 参考"
description: "DictionaryEditor 方法。删除 DictionaryEditor 中具有指定键的元素。"
type: docs
weight: 140
url: /zh/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

从 [`DictionaryEditor`](../) 中删除具有指定键的元素。

```csharp
public bool Remove(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | String | 要删除的元素的键。 |

### 返回值

如果成功删除元素则返回 true；否则返回 false。如果在原始字典中未找到键或键不可编辑，此方法也返回 false。

### 另请参见

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

从 [`DictionaryEditor`](../) 中删除特定对象的第一次出现。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 要从 [`DictionaryEditor`](../) 中删除的对象。 |

### 返回值

如果成功从 [`DictionaryEditor`](../) 中删除项则返回 true；否则返回 false。如果在原始 [`DictionaryEditor`](../) 中未找到该项，此方法也返回 false。

### 另请参见

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


