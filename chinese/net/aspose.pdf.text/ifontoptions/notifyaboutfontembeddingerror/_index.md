---
title: NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API 参考
description: 有时无法将所需的字体嵌入到文档中原因有很多例如 许可证限制或目标计算机上未找到所需字体 出现这种情况时并非简单地检测到因为所需字体是通过属性标志Font.IsEmbedded  true的设置 嵌入的当然可以在设置后立即读取此属性但是 这不是方便的方法标志 NotifyAboutFontEmbeddingError 在尝试嵌入字体失败的情况下强制执行异常机制 如果设置了此标志则 type 的异常FontEmbeddingExceptionaspose.pdf/fontembeddingexception将被抛出默认为 false.
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

有时无法将所需的字体嵌入到文档中。原因有很多，例如 许可证限制或目标计算机上未找到所需字体。 出现这种情况时，并非简单地检测到，因为所需字体是通过属性标志Font.IsEmbedded = true的设置 嵌入的；当然，可以在设置后立即读取此属性，但是 这不是方便的方法。标志 NotifyAboutFontEmbeddingError 在尝试嵌入字体失败的情况下强制执行异常机制 。如果设置了此标志，则 type 的异常[`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception)将被抛出。默认为 false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 也可以看看

* interface [IFontOptions](../../ifontoptions)
* 命名空间 [Aspose.Pdf.Text](../../ifontoptions)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
