---
title: IOpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Mevcut bir asistanı asenkron olarak siler
type: docs
weight: 130
url: /tr/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync metodu

Mevcut bir asistanı asenkron olarak siler.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assistantId | String | Silinecek asistanın kimliği. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, silme işleminin durumunu içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Asistan kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [DeleteStatusResponse](../../deletestatusresponse/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)