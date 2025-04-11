---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot metodu. Verilen mesaj için asenkron olarak bir yanıt alır
type: docs
weight: 20
url: /tr/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Verilen mesaj için asenkron olarak bir yanıt alır.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | String | Yanıt istenen girdi mesajı. |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Yanıt dizesi ile asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Verilen mesajlar listesinin yanıtını asenkron olarak alır.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| messages | List`1 | Yanıt istenen girdi mesajlarının listesi. |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Yanıt dizesi ile asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)