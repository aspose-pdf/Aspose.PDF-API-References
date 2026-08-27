---
title: "CosPdfDictionary.TryGetValue"
second_title: "Aspose.PDF for .NET API 参考"
description: "CosPdfDictionary 方法。用于访问字符串、名称、布尔值、数字等简单数据类型。对其他类型返回 null"
type: docs
weight: 170
url: /zh/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

用于访问字符串、名称、布尔值、数字等简单数据类型。对其他类型返回 null。

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | String | 键值 |
| value | ICosPdfPrimitive& | 返回键对应的 [`ICosPdfPrimitive`](../../icospdfprimitive/) 或 null。 |

### 返回值

如果 [`ICosPdfPrimitive`](../../icospdfprimitive/) 类似于字符串、名称、布尔值、数字则返回 true。对所有其他类型返回 false。

### 另请参见

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


