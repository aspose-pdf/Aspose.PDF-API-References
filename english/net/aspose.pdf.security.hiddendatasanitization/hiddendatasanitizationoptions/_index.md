---
title: "HiddenDataSanitizationOptions Class"
linktitle: "HiddenDataSanitizationOptions"
articleTitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.HiddenDataSanitization.HiddenDataSanitizationOptions class. Represents the configuration options for sanitizing hidden data within a docu..."
type: docs
weight: 20
url: "/net/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/"
keywords: "HiddenDataSanitizationOptions, Aspose.Pdf.Security.HiddenDataSanitization, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## HiddenDataSanitizationOptions class

Represents the configuration options for sanitizing hidden data within a document.

```csharp
public sealed class HiddenDataSanitizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HiddenDataSanitizationOptions](./hiddendatasanitizationoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertPagesToImages](./convertpagestoimages/) { get; set; } | Gets or sets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the `All` method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [FlattenForms](./flattenforms/) { get; set; } | Gets or sets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [FlattenLayers](./flattenlayers/) { get; set; } | Gets or sets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [ImageCompressionOptions](./imagecompressionoptions/) { get; set; } | Gets or sets the document image conversion option. The option must be enabled manually when using the `All` method if it is required. |
| [ImageDpi](./imagedpi/) { get; set; } | Gets or sets the option to resolve page images during conversion. |
| [RemoveAnnotations](./removeannotations/) { get; set; } | Gets or sets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [RemoveAttachments](./removeattachments/) { get; set; } | Gets or sets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [RemoveJavaScriptsAndActions](./removejavascriptsandactions/) { get; set; } | Gets or sets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [RemoveMetadata](./removemetadata/) { get; set; } | Gets or sets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [RemoveSearchIndexAndPrivateInfo](./removesearchindexandprivateinfo/) { get; set; } | Gets or sets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |

## Methods

| Name | Description |
| --- | --- |
| static [All](./all/)() | Creates a new instance of the [`HiddenDataSanitizationOptions`](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/) class with all options set for sanitization. This includes enabling the removal of annotations, JavaScript, metadata, attachments, search index, private information, flattening of forms and layers, while disabling the option to convert pages to images. Optional configurations like `ImageCompressionOptions` or `ConvertPagesToImages` can be manually modified after obtaining the instance, as they are not active by default. |

### See Also

* namespace [Aspose.Pdf.Security.HiddenDataSanitization](../../aspose.pdf.security.hiddendatasanitization/)
* assembly [Aspose.PDF](../../)

