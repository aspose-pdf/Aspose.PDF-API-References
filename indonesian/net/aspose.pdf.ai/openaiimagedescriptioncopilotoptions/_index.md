---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Mewakili opsi untuk mengonfigurasi OpenAICopilot
type: docs
weight: 900
url: /id/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## Kelas OpenAIImageDescriptionCopilotOptions

Mewakili opsi untuk mengonfigurasi OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Mendapatkan atau mengatur nama asisten. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Mendapatkan atau mengatur koleksi dokumen yang akan diproses. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Mendapatkan atau mengatur prompt untuk menginstruksikan model memberikan deskripsi gambar. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Mendapatkan atau mengatur tingkat detail gambar jika ditentukan oleh pengguna. "low" menggunakan lebih sedikit token, Anda dapat memilih resolusi tinggi menggunakan "high". Jika tidak diatur, default ke "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token penyelesaian yang dapat digunakan selama proses. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token prompt yang dapat digunakan selama proses. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Mendapatkan atau mengatur model visi yang akan digunakan untuk asisten. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Mendapatkan atau mengatur jalur file untuk file teks yang berisi instruksi sistem asisten. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Mendapatkan atau mengatur suhu pengambilan sampel yang akan digunakan untuk model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Mendapatkan atau mengatur nilai top-p untuk pengambilan sampel nucleus. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Membuat instance baru dari `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Membuat instance dari `OpenAIImageDescriptionCopilotOptions` dan mengonfigurasinya menggunakan delegasi yang diberikan. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Mendapatkan `OpenAIImageDescriptionCopilotOptions` saat ini. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Mengatur nama asisten untuk opsi copilot deskripsi gambar. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Menambahkan dokumen PDF ke koleksi dokumen untuk opsi copilot deskripsi gambar. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Menambahkan jalur dokumen ke koleksi dokumen untuk opsi copilot deskripsi gambar. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Mengatur koleksi dokumen untuk opsi copilot deskripsi gambar. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Menambahkan beberapa dokumen PDF ke koleksi dokumen untuk opsi copilot deskripsi gambar. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Menambahkan beberapa jalur dokumen ke koleksi dokumen untuk opsi copilot deskripsi gambar. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Mengatur prompt untuk opsi copilot deskripsi gambar. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Mengatur tingkat detail gambar. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Mengatur instruksi untuk opsi copilot deskripsi gambar. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Mengatur token penyelesaian maksimum untuk opsi copilot deskripsi gambar. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Mengatur token prompt maksimum untuk opsi copilot deskripsi gambar. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Mengatur model untuk opsi copilot deskripsi gambar. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Mengatur suhu untuk opsi copilot deskripsi gambar. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Mengatur nilai top P untuk opsi copilot deskripsi gambar. |

### Lihat Juga

* kelas [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* antarmuka [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)