---
title: "Page.IsBlank"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 方法。获取页面是否为空的标志。"
type: docs
weight: 490
url: /zh/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

获取页面是否为空的标志。

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillThresholdFactor | Double | 用于管理检测灵敏度的填充阈值。应在范围 [0..1) 之间。 |

### 返回值

True - 如果页面为空；否则为 false。

## 备注

为了确定页面是否为空，会计算已填充空间与页面总空间的比例。将该比例与 fillThresholdFactor 参数进行比较，如果小于该阈值，则认为页面为空。

### 另请参见

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


