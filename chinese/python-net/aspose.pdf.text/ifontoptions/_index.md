---
title: "IFontOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于调节字体行为的有用属性"
type: docs
weight: 180
url: /zh/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

用于调节字体行为的有用属性

IFontOptions 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| notify_about_font_embedding_error | 有时无法将所需字体嵌入文档。原因有很多，例如<br/>            许可证限制或在目标计算机上未找到所需字体。<br/>            当出现这种情况时并不容易检测，因为所需字体是通过设置 <br/>            属性标志 Font.IsEmbedded = true 来嵌入的；当然可以在设置后立即读取此属性，但<br/>            这并不是方便的方法。标志 NotifyAboutFontEmbeddingError 强制使用异常机制 <br/>            来处理嵌入字体失败的情况。如果设置了此标志，将抛出类型为<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) 的异常。默认值为 false. |

### 另请参阅

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

