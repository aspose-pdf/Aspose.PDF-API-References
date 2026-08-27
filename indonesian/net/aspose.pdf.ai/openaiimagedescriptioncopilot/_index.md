---
title: "Kelas OpenAIImageDescriptionCopilot"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Menyediakan fungsionalitas pemrosesan gambar untuk kelas OpenAICopilot. Contoh penggunaan untuk membuat konfigurasi klien OpenAI dengan opsi ImageDescriptionCopilot dan penggunaan copilot untuk menghasilkan deskripsi gambar serta menambahkan deskripsi ke dokumen yang terlampir."
type: docs
weight: 940
url: /id/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## OpenAIImageDescriptionCopilot class

Menyediakan fungsionalitas pemrosesan gambar untuk kelas OpenAICopilot. Contoh penggunaan membuat klien OpenAI, konfigurasi opsi ImageDescriptionCopilot, dan penggunaan copilot untuk menghasilkan deskripsi gambar serta menambahkan deskripsi ke dokumen yang dilampirkan.

```csharp
// Buat klien AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Buat opsi copilot.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...buat menggunakan delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument(new PdfDocument // Attach documents.
    {
        Name = "Another_Pdf_with_images",
        Document = new Document(GetInputPath("Pdf_with_images_low_res_bw.pdf"))
    })
    .WithDocument(GetInputPath("Mona_liza.jpg")) // Attach images
    .WithDocument(GetInputPath("Pdf_with_images.pdf")); // Attach document paths.

// Buat copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Dapatkan deskripsi gambar.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Gunakan metode ekstensi untuk menambahkan deskripsi gambar ke dokumen yang terlampir.
await copilot.AddPdfImageDescriptionsAsync("DocumentsOutputDirectory");
```

```csharp
public class OpenAIImageDescriptionCopilot : IImageDescriptionCopilot
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OpenAIImageDescriptionCopilot](openaiimagedescriptioncopilot/)(IOpenAIClient, IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Menginisialisasi instance baru dari kelas `OpenAIImageDescriptionCopilot`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaiimagedescriptioncopilot/hascontext/) { get; } |  |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetImageDescriptionsAsync](../../aspose.pdf.ai/openaiimagedescriptioncopilot/getimagedescriptionsasync/)(CancellationToken?) |  |

### Lihat Juga

* interface [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


