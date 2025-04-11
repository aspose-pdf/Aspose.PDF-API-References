---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage sınıfı. Model tarafından oluşturulan bir sohbet tamamlama mesajı
type: docs
weight: 190
url: /tr/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage sınıfı

Model tarafından oluşturulan bir sohbet tamamlama mesajı.

```csharp
public class ChatMessage
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | `ChatMessage` sınıfının yeni bir örneğini başlatır. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | `ChatMessage` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Mesajın içeriğini alır veya ayarlar. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Katılımcı için isteğe bağlı bir ad alır veya ayarlar. Aynı rolün katılımcılarını ayırt etmek için model bilgilerini sağlar. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Mesajın yazarının rolünü alır veya ayarlar. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Bu mesajın yanıt verdiği araç çağrısını alır veya ayarlar. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Model tarafından oluşturulan araç çağrılarını, örneğin işlev çağrılarını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Bir asistan mesajını temsil eden yeni bir ChatMessage nesnesi oluşturur. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Bir sistem mesajını temsil eden yeni bir ChatMessage nesnesi oluşturur. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Bir kullanıcı mesajını temsil eden yeni bir ChatMessage nesnesi oluşturur. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)