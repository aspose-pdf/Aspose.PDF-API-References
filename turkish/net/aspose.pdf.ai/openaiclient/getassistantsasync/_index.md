---
title: OpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Asenkron olarak asistanların listesini alır
type: docs
weight: 200
url: /tr/net/aspose.pdf.ai/openaiclient/getassistantsasync/
---
## OpenAIClient.GetAssistantsAsync metodu

Asenkron olarak asistanların listesini alır.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Asistanlar listesini filtrelemek için isteğe bağlı sorgu parametreleri. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu asistanlar listesini içerir.

### Ayrıca Bakınız

* sınıf [AssistantListResponse](../../assistantlistresponse/)
* sınıf [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)