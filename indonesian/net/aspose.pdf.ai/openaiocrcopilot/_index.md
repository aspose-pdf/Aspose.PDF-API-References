---
title: "Kelas OpenAIOcrCopilot"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OpenAIOcrCopilot. Menyediakan kemampuan OCR untuk mengekstrak teks dari dokumen PDF dan gambar. Jenis gambar yang didukung PNG .png JPEG .jpeg dan .jpg WEBP .webp GIF .gif yang tidak beranimasi. Contoh penggunaan untuk membuat klien OpenAI, mengkonfigurasi opsi, dan menggunakan OCR copilot"
type: docs
weight: 980
url: /id/net/aspose.pdf.ai/openaiocrcopilot/
---
## OpenAIOcrCopilot class

Menyediakan kemampuan OCR untuk mengekstrak teks dari dokumen PDF dan gambar. Jenis gambar yang didukung: PNG (.png), JPEG (.jpeg dan .jpg), WEBP (.webp), GIF non-animasi (.gif). Contoh penggunaan membuat klien OpenAI, mengonfigurasi opsi, dan menggunakan OCR copilot.

```csharp
// Buat klien AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    //.WithOrganization("org_123") // Mengonfigurasi parameter opsional.
    .Build(); // Build

// Buat opsi copilot.
var options = OpenAIOcrCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt4O; }) // ...membuat menggunakan delegasi.
    .WithDocument("DocumentInputPath"); // .WithDocument methods allows to add Document objects and paths to PDF documents and images.

// Buat copilot ringkasan.
IOcrCopilot ocrCopilot = AICopilotFactory.CreateOcrCopilot(openAiClient, options);

// Dapatkan pengenalan teks.
List<TextRecognitionResult> textRecognitions = await ocrCopilot.GetTextRecognitionResultAsync();

// Akses ke teks yang diekstrak.
string text = textRecognitions[0].OcrDetails[0].ExtractedText;
```

```csharp
public class OpenAIOcrCopilot : IOcrCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OpenAIOcrCopilot](openaiocrcopilot/)(IOpenAIClient, IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Menginisialisasi instance baru dari kelas `OpenAIOcrCopilot`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiocrcopilot/hascontext/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetTextRecognitionResultAsync](../../aspose.pdf.ai/openaiocrcopilot/gettextrecognitionresultasync/)(CancellationToken?) |  |

### Lihat Juga

* interface [IOcrCopilot](../iocrcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


