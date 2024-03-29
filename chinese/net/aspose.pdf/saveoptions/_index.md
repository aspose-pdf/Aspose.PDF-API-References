---
title: SaveOptions
second_title: Aspose.PDF for .NET API 参考
description: SaveOptions 类型保持单个保存选项的抽象级别
type: docs
weight: 6290
url: /zh/net/aspose.pdf/saveoptions/
---
## SaveOptions class

SaveOptions 类型保持单个保存选项的抽象级别

```csharp
public abstract class SaveOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | 获取或设置布尔值，指示在文档保存到响应后将关闭响应对象。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | 回调以处理生成的任何警告。 WarningHandler 返回指定 Continue 或 Abort 的 ReturnAction 枚举项。 Continue 是默认操作，Save 操作继续，但是用户也可以返回 Abort，在这种情况下 Save 操作应该停止。 |

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
