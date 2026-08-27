---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF for .NET API 参考"
description: "XImage 方法。设置页面上 XImage 的替代文本"
type: docs
weight: 180
url: /zh/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

在页面上为 XImage 设置替代文本。

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alternativeText | String | 要指定的替代文本。 |
| 页面 | 页面 | XImage 所在的页面。 |

### 返回值

如果为 XImage 设置了 alternativeText，则为 True；如果未设置，则为 False。

## 备注

该方法在以下情况下返回 false：- 在指定页面未找到 XImage。- XImage 在页面上出现多次，且具有不同的结构元素，导致无法确定应为哪个实例设置替代文本。

### 另请参见

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


