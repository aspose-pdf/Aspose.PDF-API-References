---
title: Class OpenAIImageDescriptionCopilot
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.OpenAIImageDescriptionCopilot. Menyediakan fungsionalitas pemrosesan gambar untuk kelas OpenAICopilot. Contoh penggunaan untuk membuat konfigurasi klien OpenAI dari opsi ImageDescriptionCopilot dan penggunaan copilot untuk menghasilkan deskripsi gambar dan menambahkan deskripsi ke dokumen yang dilampirkan
type: docs
weight: 880
url: /id/net/aspose.pdf.ai/openaiimagedescriptioncopilot/
---
## Kelas OpenAIImageDescriptionCopilot

Menyediakan fungsionalitas pemrosesan gambar untuk kelas OpenAICopilot. Contoh penggunaan untuk membuat klien OpenAI, konfigurasi opsi ImageDescriptionCopilot, dan penggunaan copilot untuk menghasilkan deskripsi gambar dan menambahkan deskripsi ke dokumen yang dilampirkan.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Create copilot options.
var options = OpenAIImageDescriptionCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
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

// Create copilot.
var copilot = AICopilotFactory.CreateImageDescriptionCopilot(openAiClient, options);

// Get Image descriptions.
List<ImageDescriptionResult> imageDescriptions = await copilot.GetImageDescriptionsAsync();

// Use extension method to add image descriptions to attached documents.
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

* antarmuka [IImageDescriptionCopilot](../iimagedescriptioncopilot/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)