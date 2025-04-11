---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient metodu. Belirtilen threadId ve runCreateRequest ile asistanı çalıştırır ve asistan yanıtını asenkron olarak alır.
type: docs
weight: 440
url: /tr/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync metodu

Belirtilen threadId ve runCreateRequest ile asistanı çalıştırır ve asenkron olarak asistan yanıtını alır.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threadId | String | İpucu kimliği. |
| runCreateRequest | RunCreateRequest | Çalıştırma oluşturma isteği. |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Asistan yanıt dizesi ile asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* sınıf [RunCreateRequest](../../runcreaterequest/)
* sınıf [OpenAIClient](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)