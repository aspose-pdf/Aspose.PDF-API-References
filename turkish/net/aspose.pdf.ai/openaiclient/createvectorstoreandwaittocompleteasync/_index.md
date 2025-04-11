---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Yeni bir vektör deposu oluşturur ve tamamlanmasını asenkron olarak bekler
type: docs
weight: 90
url: /tr/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync metodu

Yeni bir vektör deposu oluşturur ve tamamlanmasını asenkron olarak bekler.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | Vektör deposunu oluşturmak için detayları içeren istek nesnesi. |
| cancellationToken | Nullable`1 | İşlemi iptal etmek için bir token. |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev. Görev sonucu, tamamlandıktan sonra vektör deposu oluşturma yanıtını içerir.

### Ayrıca Bakınız

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)