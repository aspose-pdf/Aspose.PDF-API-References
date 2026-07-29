---
title: "类 SaveableFacade"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.SaveableFacade 类。所有可保存外观的基类。"
type: docs
weight: 4820
url: /zh/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class

所有可保存外观的基类。

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 初始化 facade。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 初始化 facade。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | 将 PDF 文档保存到指定的流中。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | 将 PDF 文档保存到指定的文件中。 |

### 另请参见

* class [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


