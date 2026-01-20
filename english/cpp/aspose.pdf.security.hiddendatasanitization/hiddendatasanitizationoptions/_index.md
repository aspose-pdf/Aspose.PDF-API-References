---
title: Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions class
linktitle: HiddenDataSanitizationOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions class. Represents the configuration options for sanitizing hidden data within a document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/
---
## HiddenDataSanitizationOptions class


Represents the configuration options for sanitizing hidden data within a document.

```cpp
class HiddenDataSanitizationOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [All](./all/)() | Creates a new instance of the [HiddenDataSanitizationOptions](./) class with all options set for sanitization. This includes enabling the removal of annotations, JavaScript, metadata, attachments, search index, private information, flattening of forms and layers, while disabling the option to convert pages to images. Optional configurations like [ImageCompressionOptions](../) or [ConvertPagesToImages](../) can be manually modified after obtaining the instance, as they are not active by default. |
| [get_ConvertPagesToImages](./get_convertpagestoimages/)() const | Gets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the [All](./all/) method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [get_FlattenForms](./get_flattenforms/)() const | Gets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [get_FlattenLayers](./get_flattenlayers/)() const | Gets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Gets the document image conversion option. The option must be enabled manually when using the [All](./all/) method if it is required. |
| [get_ImageDpi](./get_imagedpi/)() const | Gets the option to resolve page images during conversion. |
| [get_RemoveAnnotations](./get_removeannotations/)() const | Gets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [get_RemoveAttachments](./get_removeattachments/)() const | Gets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [get_RemoveJavaScriptsAndActions](./get_removejavascriptsandactions/)() const | Gets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [get_RemoveMetadata](./get_removemetadata/)() const | Gets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [get_RemoveSearchIndexAndPrivateInfo](./get_removesearchindexandprivateinfo/)() const | Gets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |
| [HiddenDataSanitizationOptions](./hiddendatasanitizationoptions/)() |  |
| [set_ConvertPagesToImages](./set_convertpagestoimages/)(bool) | Sets the option to convert pages to images. If this option is enabled, the ImageCompressionOptions option will be ignored. The option must be enabled manually when using the [All](./all/) method if it is required. The conversion of pages to images will occur after clearing the main hidden data, which is controlled by other options. |
| [set_FlattenForms](./set_flattenforms/)(bool) | Sets a value indicating whether forms in the document should be flattened during the sanitization process. Flattening forms converts interactive form fields into static content, making them non-editable or fillable. |
| [set_FlattenLayers](./set_flattenlayers/)(bool) | Sets the option to flatten the layers in the PDF document. When enabled, all layers in the document are merged into a single layer, removing their separate structure. This option is useful for sanitizing documents by simplifying their content and ensuring no hidden data resides within layers. |
| [set_ImageCompressionOptions](./set_imagecompressionoptions/)(System::SharedPtr\<Aspose::Pdf::Optimization::ImageCompressionOptions\>) | Sets the document image conversion option. The option must be enabled manually when using the [All](./all/) method if it is required. |
| [set_ImageDpi](./set_imagedpi/)(int32_t) | Sets the option to resolve page images during conversion. |
| [set_RemoveAnnotations](./set_removeannotations/)(bool) | Sets a value indicating whether to remove annotations from the document. When enabled, all annotations present in the document will be removed during the sanitization process. Redact annotations will be applied. |
| [set_RemoveAttachments](./set_removeattachments/)(bool) | Sets the option to remove all attached files from the document. When enabled, it ensures that any attachments within the PDF are eliminated during the sanitation process. |
| [set_RemoveJavaScriptsAndActions](./set_removejavascriptsandactions/)(bool) | Sets a value indicating whether JavaScript and associated actions should be removed from the document. This option is useful to eliminate potential security vulnerabilities introduced by embedded scripts. |
| [set_RemoveMetadata](./set_removemetadata/)(bool) | Sets an option to remove metadata from the document. If set to true, metadata such as document properties and additional embedded metadata information will be removed during sanitization. |
| [set_RemoveSearchIndexAndPrivateInfo](./set_removesearchindexandprivateinfo/)(bool) | Sets a value indicating whether the search index and private information should be removed from the document. Enables the removal of embedded search indices and private data to enhance document security and privacy. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
