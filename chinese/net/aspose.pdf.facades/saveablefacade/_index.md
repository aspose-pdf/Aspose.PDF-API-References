---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.SaveableFacade 类。所有可保存外观的基类
type: docs
weight: 4700
url: /zh/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class

所有可保存外观的基类。

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取外观正在处理的文档。 |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化外观。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化外观。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | 将 PDF 文档保存到指定的流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | 将 PDF 文档保存到指定的文件。 |

### See Also

* class [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)