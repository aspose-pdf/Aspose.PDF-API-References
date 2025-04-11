---
title: Class MessageContentRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.MessageContentRequest 类。消息内容为文本和/或图像的数组
type: docs
weight: 780
url: /zh/net/aspose.pdf.ai/messagecontentrequest/
---
## MessageContentRequest 类

消息内容为文本和/或图像的数组。

```csharp
public class MessageContentRequest : MessageContentBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MessageContentRequest](messagecontentrequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ImageFile](../../aspose.pdf.ai/messagecontentbase/imagefile/) { get; set; } | 获取或设置消息内容中的图像文件。 |
| [ImageUrl](../../aspose.pdf.ai/messagecontentbase/imageurl/) { get; set; } | 获取或设置消息内容中的图像 URL。 |
| [MessageContentType](../../aspose.pdf.ai/messagecontentbase/messagecontenttype/) { get; set; } | 获取或设置内容的类型。 |
| [Text](../../aspose.pdf.ai/messagecontentrequest/text/) { get; set; } | 获取或设置消息的一部分的文本内容。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateImageFileContent](../../aspose.pdf.ai/messagecontentrequest/createimagefilecontent/)(string, string) | 为消息创建图像文件内容。 |
| static [CreateImageUrlContent](../../aspose.pdf.ai/messagecontentrequest/createimageurlcontent/)(string, string) | 为消息创建图像 URL 内容。 |
| static [CreateTextContent](../../aspose.pdf.ai/messagecontentrequest/createtextcontent/)(string) | 为消息创建文本内容。 |

### 另见

* 类 [MessageContentBase](../messagecontentbase/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)