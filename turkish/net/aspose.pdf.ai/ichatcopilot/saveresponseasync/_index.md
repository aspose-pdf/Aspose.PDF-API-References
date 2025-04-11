---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot metodu. Verilen mesaj için yanıtı asenkron olarak bir PDF dosyasına kaydeder
type: docs
weight: 40
url: /tr/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Verilen mesaj için yanıtı asenkron olarak bir PDF dosyasına kaydeder.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | String | Yanıtın kaydedileceği giriş mesajı. |
| outputFileName | String | Yanıtı kaydetmek için çıkış PDF dosyasının adı. |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Verilen mesaj için yanıtı belirtilen formatta bir dosyaya asenkron olarak kaydeder.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | String | Yanıtın kaydedileceği giriş mesajı. |
| outputFileName | String | Yanıtı kaydetmek için çıkış dosyasının adı. |
| saveFormat | SaveFormat | Yanıtın kaydedileceği format (belirtilmezse PDF). |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Verilen mesajlar listesinin yanıtlarını asenkron olarak bir PDF dosyasına kaydeder.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| messages | List`1 | Yanıtların kaydedileceği giriş mesajları listesi. |
| outputFileName | String | Yanıtları kaydetmek için çıkış PDF dosyasının adı. |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Verilen mesajlar listesinin yanıtlarını belirtilen formatta bir dosyaya asenkron olarak kaydeder.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| messages | List`1 | Yanıtların kaydedileceği giriş mesajları listesi. |
| outputFileName | String | Yanıtları kaydetmek için çıkış dosyasının adı. |
| saveFormat | SaveFormat | Yanıtların kaydedileceği format (belirtilmezse PDF). |
| cancellationToken | Nullable`1 | İptal belirteci (isteğe bağlı). |

### Dönüş Değeri

Asenkron işlemi temsil eden bir görev.

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* arayüz [IChatCopilot](../)
* ad alanı [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../../)