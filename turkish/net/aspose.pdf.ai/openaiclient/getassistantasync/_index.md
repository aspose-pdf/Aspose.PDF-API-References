---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient yöntemi. Belirli bir asistanın ayrıntılarını asenkron olarak alır
type: docs
weight: 190
url: /tr/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync yöntemi

Belirli bir asistanın ayrıntılarını asenkron olarak alır.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assistantId | String | Alınacak asistanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir jeton. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, asistanın ayrıntılarını içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Asistan kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [AssistantResponse](../../assistantresponse/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)