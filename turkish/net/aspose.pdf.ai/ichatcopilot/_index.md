---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot arayüzü. AI modelleri aracılığıyla belgelerle etkileşimde bulunan bir sohbet yardımcı pilotunu temsil eder.
type: docs
weight: 470
url: /tr/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot arayüzü

AI modelleri aracılığıyla belgelerle etkileşimde bulunan bir sohbet yardımcı pilotunu temsil eder.

```csharp
public interface IChatCopilot : IAICopilot
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Bağlamı asenkron olarak siler. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Verilen mesajlar listesi için asenkron olarak bir yanıt alır. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Verilen mesaj için asenkron olarak bir yanıt alır. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Bağlamı bir JSON dosyasına asenkron olarak kaydeder. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Verilen mesajlar listesi için yanıtları bir PDF dosyasına asenkron olarak kaydeder. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Verilen mesaj için yanıtı bir PDF dosyasına asenkron olarak kaydeder. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Verilen mesajlar listesi için yanıtları belirtilen formatta bir dosyaya asenkron olarak kaydeder. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Verilen mesaj için yanıtı belirtilen formatta bir dosyaya asenkron olarak kaydeder. |

### Ayrıca Bakınız

* arayüz [IAICopilot](../iaicopilot/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)