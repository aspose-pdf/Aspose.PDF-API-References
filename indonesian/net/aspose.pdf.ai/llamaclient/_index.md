---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.LlamaClient. Mewakili klien untuk berinteraksi dengan API Llama
type: docs
weight: 700
url: /id/net/aspose.pdf.ai/llamaclient/
---
## Kelas LlamaClient

Mewakili klien untuk berinteraksi dengan API Llama.

Mewakili klien untuk berinteraksi dengan API Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Mendapatkan atau mengatur penundaan backoff dalam detik. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum percobaan ulang permintaan HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Mendapatkan atau mengatur interval polling dalam detik. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Mendapatkan atau mengatur batas waktu polling dalam detik. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Membuat permintaan penyelesaian obrolan di layanan Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Menghapus sumber daya yang digunakan oleh [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Mendapatkan instance dari [`ISummaryCopilot`](../isummarycopilot/) dengan opsi yang ditentukan. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Membuat instance baru dari [`Builder`](../llamaclient.builder/) dengan kunci API yang diberikan. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| kelas [Builder](../../aspose.pdf.ai/llamaclient.builder) | Kelas Builder untuk membuat instance dari `LlamaClient`. |

### Lihat Juga

* kelas [AIClientBase](../aiclientbase/)
* antarmuka [ILlamaClient](../illamaclient/)
* antarmuka [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* kelas [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)