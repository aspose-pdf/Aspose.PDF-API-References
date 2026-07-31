---
title: "Kelas TruncationStrategy"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.TruncationStrategy. Mewakili strategi pemotongan yang mengontrol bagaimana thread akan dipotong sebelum dijalankan."
type: docs
weight: 1330
url: /id/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

Mewakili strategi pemotongan yang mengatur bagaimana sebuah thread akan dipotong sebelum dijalankan.

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
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | Mendapatkan atau mengatur jumlah pesan terbaru dari thread saat membangun konteks untuk eksekusi. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | Mendapatkan atau mengatur strategi pemotongan yang digunakan untuk thread. Defaultnya adalah auto. Jika diatur ke last_messages, thread akan dipotong menjadi n pesan terbaru dalam thread. Ketika diatur ke auto, pesan-pesan di tengah thread akan dihapus untuk menyesuaikan panjang konteks model, max_prompt_tokens. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


