---
title: IOpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient metodu. Mevcut bir ipliği asenkron olarak değiştirir
type: docs
weight: 380
url: /tr/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## IOpenAIClient.ModifyThreadAsync metodu

Mevcut bir ipliği asenkron olarak değiştirir.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | Değiştirilecek ipliğin kimliği. |
| threadModifyRequest | ThreadModifyRequest | Değişiklik detaylarını içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, iplik değişikliğinden gelen yanıtı içerir.

### İstisnalar

| istisna | durum |
| --- | --- |
| [AIClientException](../../aiclientexception/) | İplik kimliği null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız

* sınıf [ThreadResponse](../../threadresponse/)
* sınıf [ThreadModifyRequest](../../threadmodifyrequest/)
* arayüz [IOpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)