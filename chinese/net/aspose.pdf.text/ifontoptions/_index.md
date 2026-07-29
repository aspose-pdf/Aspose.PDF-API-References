---
title: "接口 IFontOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.IFontOptions 接口。用于调节字体行为的有用属性"
type: docs
weight: 10790
url: /zh/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

用于调节 Font 行为的有用属性

```csharp
public interface IFontOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 有时无法将所需字体嵌入文档中。原因有很多，例如许可证限制或在目标计算机上未找到所需字体。出现这种情况时并不容易检测，因为所需字体是通过属性标志 Font.IsEmbedded = true 嵌入的；当然可以在设置后立即读取该属性，但这并不方便。标志 NotifyAboutFontEmbeddingError 为嵌入字体失败的情况强制使用异常机制。如果设置了此标志，将抛出类型为 [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) 的异常。默认值为 false。 |

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


