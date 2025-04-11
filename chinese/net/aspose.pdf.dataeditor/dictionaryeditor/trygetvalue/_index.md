---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor 方法。用于访问简单数据类型，如字符串、名称、布尔值、数字。对于其他类型返回 null
type: docs
weight: 150
url: /zh/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue 方法

用于访问简单数据类型，如字符串、名称、布尔值、数字。对于其他类型返回 null。

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | String | 键值 |
| value | ICosPdfPrimitive& | 返回 [`ICosPdfPrimitive`](../../icospdfprimitive/) 对于键或 null。 |

### 返回值

如果 [`ICosPdfPrimitive`](../../icospdfprimitive/) 类似于字符串、名称、布尔值、数字，则返回 true。对于所有其他类型返回 false。

### 另请参阅

* 接口 [ICosPdfPrimitive](../../icospdfprimitive/)
* 类 [DictionaryEditor](../)
* 命名空间 [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* 程序集 [Aspose.PDF](../../../)