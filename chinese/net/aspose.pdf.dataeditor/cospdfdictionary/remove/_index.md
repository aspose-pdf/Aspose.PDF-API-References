---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary 方法。 从 CosPdfDictionary 中移除具有指定键的元素
type: docs
weight: 150
url: /zh/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

从 [`CosPdfDictionary`](../) 中移除具有指定键的元素。

```csharp
public bool Remove(string key)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | 字符串 | 要移除的元素的键。 |

### 返回值

如果元素成功移除，则返回 true；否则返回 false。如果在原始字典中未找到键，或者键不可编辑，则此方法也返回 false。

### 另请参阅

* 类 [CosPdfDictionary](../)
* 命名空间 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 程序集 [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

从 [`CosPdfDictionary`](../) 中移除特定对象的第一次出现。

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | KeyValuePair`2 | 要从 [`CosPdfDictionary`](../) 中移除的对象。 |

### 返回值

如果 item 成功从 [`CosPdfDictionary`](../) 中移除，则返回 true；否则返回 false。如果在原始 [`CosPdfDictionary`](../) 中未找到 item，则此方法也返回 false。

### 另请参阅

* 接口 [ICosPdfPrimitive](../../icospdfprimitive/)
* 类 [CosPdfDictionary](../)
* 命名空间 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 程序集 [Aspose.PDF](../../../)