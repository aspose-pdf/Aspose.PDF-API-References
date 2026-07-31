---
title: "Kelas OpenAIChatCopilot"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OpenAIChatCopilot. Mewakili copilot obrolan untuk berinteraksi dengan dokumen melalui model AI. Contoh penggunaan membuat klien OpenAI, mengonfigurasi opsi, dan menggunakan ChatCopilot untuk berinteraksi dengan kueri pengguna serta mengelola konteks percakapan"
type: docs
weight: 880
url: /id/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

Mewakili copilot obrolan untuk berinteraksi dengan dokumen melalui model AI. Contoh penggunaan membuat klien OpenAI, mengonfigurasi opsi, dan menggunakan ChatCopilot untuk berinteraksi dengan pertanyaan pengguna serta mengelola konteks percakapan.

```csharp
// Buat klien AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Buat opsi copilot.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...buat menggunakan delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// Buat copilot ringkasan.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// Dapatkan respons atas kueri pengguna.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// Dapatkan respons atas daftar kueri.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// Simpan ringkasan sebagai dokumen PDF.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// Simpan ringkasan dengan format yang ditentukan.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// Simpan ringkasan sebagai dokumen PDF.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// Simpan ringkasan dengan format yang ditentukan.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// Simpan konteks.
await chatCopilot.SaveContextAsync("outputPath");

// Hapus konteks.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Menginisialisasi instance baru dari kelas `OpenAIChatCopilot` dengan klien dan opsi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### Lihat Juga

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


