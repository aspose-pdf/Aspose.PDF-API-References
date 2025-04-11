---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Yeni bir asistanı asenkron olarak oluşturur
type: docs
weight: 30
url: /tr/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## IOpenAIClient.CreateAssistantAsync metodu

Yeni bir asistanı asenkron olarak oluşturur.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | Asistanı oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, asistan oluşturma yanıtını içerir.

### Ayrıca Bakınız

* sınıf [AssistantResponse](../../assistantresponse/)
* sınıf [AssistantCreateRequest](../../assistantcreaterequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)