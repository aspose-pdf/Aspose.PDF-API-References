---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptions 类。SaveOptions 类型持有单个保存选项的抽象级别
type: docs
weight: 9870
url: /zh/net/aspose.pdf/saveoptions/
---
## SaveOptions 类

SaveOptions 类型持有单个保存选项的抽象级别

```csharp
public abstract class SaveOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否缓存字体字形。提高将 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作将继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)