---
title: "类 ThreadMessageCreateRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.ThreadMessageCreateRequest 类。表示在线程中创建消息的请求"
type: docs
weight: 1210
url: /zh/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

表示在线程中创建消息的请求。

```csharp
public class ThreadMessageCreateRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | 获取或设置附加到消息的文件列表。 |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | 获取或设置消息的内容。可以是字符串或内容部件数组。 |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息很有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | 获取或设置创建消息的实体的角色。允许的值包括："user", "assistant"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | 创建一个新的 `ThreadMessageCreateRequest`，其角色设置为 Assistant。 |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | 创建一个新的 `ThreadMessageCreateRequest`，其角色设置为 User。 |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | 设置线程消息请求的附件。 |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | 向线程消息请求添加消息内容。 |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | 设置线程消息请求的消息内容。 |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | 设置线程消息请求的元数据。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


