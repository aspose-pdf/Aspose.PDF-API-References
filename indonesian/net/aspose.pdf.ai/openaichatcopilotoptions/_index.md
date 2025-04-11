---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.OpenAIChatCopilotOptions. Mewakili opsi untuk mengonfigurasi OpenAICopilot
type: docs
weight: 830
url: /id/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## Kelas OpenAIChatCopilotOptions

Mewakili opsi untuk mengonfigurasi OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Mendapatkan atau menetapkan nama asisten. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Mendapatkan atau menetapkan jalur file untuk cadangan konteks JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Mendapatkan atau menetapkan koleksi dokumen yang akan diproses. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token penyelesaian yang dapat digunakan selama proses berjalan. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token prompt yang dapat digunakan selama proses berjalan. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Mendapatkan atau menetapkan model yang digunakan untuk asisten. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah akan mengembalikan konteks dari cadangan. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Mendapatkan atau menetapkan jalur file untuk file teks yang berisi instruksi sistem asisten. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Mendapatkan atau menetapkan suhu pengambilan sampel yang digunakan untuk model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Mendapatkan atau menetapkan nilai top-p untuk pengambilan sampel nucleus. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Mendapatkan atau menetapkan strategi pemotongan untuk thread. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Mendapatkan atau menetapkan jumlah hari sebelum penyimpanan vektor kedaluwarsa. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Membuat instance baru dari `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Membuat instance dari `OpenAIChatCopilotOptions` dan mengonfigurasinya menggunakan delegasi yang diberikan. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Mendapatkan `OpenAIChatCopilotOptions` saat ini. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Menetapkan nama asisten untuk opsi chat copilot. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Menetapkan jalur file untuk cadangan konteks JSON dalam opsi chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Menambahkan dokumen PDF ke koleksi dokumen untuk opsi chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Menambahkan jalur dokumen ke koleksi dokumen untuk opsi chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Menambahkan dokumen teks ke koleksi dokumen untuk opsi chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Menetapkan koleksi dokumen untuk opsi chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Menambahkan beberapa dokumen PDF ke koleksi dokumen untuk opsi chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Menambahkan beberapa jalur dokumen ke koleksi dokumen untuk opsi chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Menambahkan beberapa dokumen teks ke koleksi dokumen untuk opsi chat copilot. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Menetapkan instruksi untuk opsi chat copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Menetapkan token penyelesaian maksimum untuk opsi chat copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Menetapkan token prompt maksimum untuk opsi chat copilot. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Menetapkan model untuk opsi chat copilot. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Menetapkan apakah akan mengembalikan konteks dari cadangan dalam opsi chat copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Menetapkan suhu untuk opsi chat copilot. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Menetapkan nilai top P untuk opsi chat copilot. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Menetapkan strategi pemotongan untuk opsi chat copilot. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Menetapkan jumlah hari untuk kedaluwarsa penyimpanan vektor dalam opsi chat copilot. |

### Lihat Juga

* kelas [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* antarmuka [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)