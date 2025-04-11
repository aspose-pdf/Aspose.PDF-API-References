---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageCreateRequest sınıfı. Bir iplik içinde bir mesaj oluşturmak için bir isteği temsil eder
type: docs
weight: 1120
url: /tr/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest sınıfı

Bir iplik içinde bir mesaj oluşturmak için bir isteği temsil eder.

```csharp
public class ThreadMessageCreateRequest
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Mesaja eklenmiş dosyaların listesini alır veya ayarlar. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Mesajın içeriğini alır veya ayarlar. Bir dize veya içerik parçalarının bir dizisi olabilir. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Bir nesneye eklenebilecek 16 anahtar-değer çiftinden oluşan bir küme alır veya ayarlar. Bu, nesne hakkında yapılandırılmış bir formatta ek bilgi depolamak için yararlı olabilir. Anahtarlar en fazla 64 karakter uzunluğunda ve değerler en fazla 512 karakter uzunluğunda olabilir. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Mesajı oluşturan varlığın rolünü alır veya ayarlar. İzin verilen değerler: "user", "assistant". |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Rolü Asistan olarak ayarlanmış yeni bir `ThreadMessageCreateRequest` oluşturur. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Rolü Kullanıcı olarak ayarlanmış yeni bir `ThreadMessageCreateRequest` oluşturur. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | İplik mesaj isteği için ekleri ayarlar. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | İplik mesaj isteğine bir mesaj içeriği ekler. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | İplik mesaj isteği için mesaj içeriklerini ayarlar. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | İplik mesaj isteği için meta verileri ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)