---
title: "Kelas LlamaSummaryCopilotOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Mewakili opsi untuk mengkonfigurasi OpenAICopilot"
type: docs
weight: 800
url: /id/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

Mewakili opsi untuk mengonfigurasi OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Mendapatkan atau mengatur koleksi dokumen yang akan diproses. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token penyelesaian yang dapat digunakan selama proses run. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Mendapatkan atau mengatur model yang akan digunakan untuk asisten. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Mendapatkan atau mengatur prompt untuk menginstruksikan model memberikan ringkasan dokumen. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Mendapatkan atau mengatur jalur file untuk file teks yang berisi instruksi sistem asisten. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Mendapatkan atau mengatur suhu sampling yang akan digunakan untuk model. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Mendapatkan atau mengatur nilai top-p untuk sampling nukleus. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Membuat instance baru dari `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Membuat instance `LlamaSummaryCopilotOptions` dan mengkonfigurasinya menggunakan delegasi yang disediakan. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Mendapatkan `LlamaSummaryCopilotOptions` saat ini. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Menambahkan dokumen PDF ke koleksi dokumen untuk opsi summary copilot. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Menambahkan jalur dokumen ke koleksi dokumen untuk opsi summary copilot. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Menambahkan dokumen teks ke koleksi dokumen untuk opsi summary copilot. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Mengatur koleksi dokumen untuk opsi summary copilot. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Menambahkan beberapa dokumen PDF ke koleksi dokumen untuk opsi summary copilot. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Menambahkan beberapa jalur dokumen ke koleksi dokumen untuk opsi summary copilot. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Menambahkan beberapa dokumen teks ke koleksi dokumen untuk opsi summary copilot. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Mengatur instruksi untuk opsi summary copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Mengatur token penyelesaian maksimum untuk opsi copilot ringkasan. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Mengatur model untuk opsi copilot ringkasan. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Mengatur prompt ringkasan untuk opsi copilot ringkasan. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Mengatur suhu untuk opsi copilot ringkasan. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Mengatur nilai top P untuk opsi copilot ringkasan. |

### Lihat Juga

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


