---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.OpenAISummaryCopilotOptions. Mewakili opsi untuk mengonfigurasi OpenAICopilot
type: docs
weight: 930
url: /id/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## Kelas OpenAISummaryCopilotOptions

Mewakili opsi untuk mengonfigurasi OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Mendapatkan atau mengatur nama asisten. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Mendapatkan atau mengatur koleksi dokumen yang akan diproses. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token penyelesaian yang dapat digunakan selama proses. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token prompt yang dapat digunakan selama proses. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Mendapatkan atau mengatur model yang akan digunakan untuk asisten. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Mendapatkan atau mengatur prompt untuk menginstruksikan model memberikan ringkasan dokumen. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Mendapatkan atau mengatur jalur file untuk file teks yang berisi instruksi sistem asisten. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Mendapatkan atau mengatur suhu pengambilan yang akan digunakan untuk model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Mendapatkan atau mengatur nilai top-p untuk pengambilan inti. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | Membuat instance baru dari `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | Membuat instance dari `OpenAISummaryCopilotOptions` dan mengonfigurasinya menggunakan delegasi yang diberikan. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Mendapatkan `OpenAISummaryCopilotOptions` saat ini. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Mengatur nama asisten untuk opsi copilot ringkasan. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Menambahkan dokumen PDF ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Menambahkan jalur dokumen ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Menambahkan dokumen teks ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Mengatur koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Menambahkan beberapa dokumen PDF ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Menambahkan beberapa jalur dokumen ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Menambahkan beberapa dokumen teks ke koleksi dokumen untuk opsi copilot ringkasan. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Mengatur instruksi untuk opsi copilot ringkasan. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Mengatur token penyelesaian maksimum untuk opsi copilot ringkasan. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Mengatur token prompt maksimum untuk opsi copilot ringkasan. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Mengatur model untuk opsi copilot ringkasan. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Mengatur prompt ringkasan untuk opsi copilot ringkasan. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Mengatur suhu untuk opsi copilot ringkasan. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Mengatur nilai top P untuk opsi copilot ringkasan. |

### Lihat Juga

* kelas [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* antarmuka [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)