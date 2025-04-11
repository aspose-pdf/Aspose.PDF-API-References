---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.TruncationStrategy. Mewakili strategi pemotongan yang mengontrol bagaimana sebuah thread akan dipotong sebelum dijalankan
type: docs
weight: 1240
url: /id/net/aspose.pdf.ai/truncationstrategy/
---
## Kelas TruncationStrategy

Mewakili strategi pemotongan yang mengontrol bagaimana sebuah thread akan dipotong sebelum dijalankan.

```csharp
public class TruncationStrategy
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Mengambil atau menetapkan jumlah pesan terbaru dari thread saat membangun konteks untuk dijalankan. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Mengambil atau menetapkan strategi pemotongan yang akan digunakan untuk thread. Defaultnya adalah auto. Jika diatur ke last_messages, thread akan dipotong menjadi n pesan terbaru dalam thread. Ketika diatur ke auto, pesan di tengah thread akan dihapus untuk menyesuaikan panjang konteks model, max_prompt_tokens. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)