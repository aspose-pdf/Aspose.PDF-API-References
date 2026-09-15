---
title: Class HiddenDataSanitizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.HiddenDataSanitization.HiddenDataSanitizationOptions class. Represents the configuration options for sanitizing hidden data within a document
type: docs
weight: 10300
url: /net/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/
---
## HiddenDataSanitizationOptions class

Represents the configuration options for sanitizing hidden data within a document.

```csharp
public sealed class HiddenDataSanitizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HiddenDataSanitizationOptions](hiddendatasanitizationoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertPagesToImages](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/convertpagestoimages/) { get; set; } | Gets or sets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the [`All`](./all/) method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [FlattenForms](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/flattenforms/) { get; set; } | Gets or sets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [FlattenLayers](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/flattenlayers/) { get; set; } | Gets or sets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [ImageCompressionOptions](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/imagecompressionoptions/) { get; set; } | Gets or sets the document image conversion option. The option must be enabled manually when using the [`All`](./all/) method if it is required. |
| [ImageDpi](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/imagedpi/) { get; set; } | Gets or sets the option to resolve page images during conversion. |
| [RemoveAnnotations](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/removeannotations/) { get; set; } | Gets or sets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [RemoveAttachments](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/removeattachments/) { get; set; } | Gets or sets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [RemoveJavaScriptsAndActions](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/removejavascriptsandactions/) { get; set; } | Gets or sets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [RemoveMetadata](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/removemetadata/) { get; set; } | Gets or sets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [RemoveSearchIndexAndPrivateInfo](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/removesearchindexandprivateinfo/) { get; set; } | Gets or sets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |

## Methods

| Name | Description |
| --- | --- |
| static [All](../../aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/all/)() | Creates a new instance of the `HiddenDataSanitizationOptions` class with all options set for sanitization. This includes enabling the removal of annotations, JavaScript, metadata, attachments, search index, private information, flattening of forms and layers, while disabling the option to convert pages to images. Optional configurations like [`ImageCompressionOptions`](./imagecompressionoptions/) or [`ConvertPagesToImages`](./convertpagestoimages/) can be manually modified after obtaining the instance, as they are not active by default. |

### See Also

* namespace [Aspose.Pdf.Security.HiddenDataSanitization](../../aspose.pdf.security.hiddendatasanitization/)
* assembly [Aspose.PDF](../../)


