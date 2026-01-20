---
title: Aspose::Pdf::Facades::DefaultMetadataProperties enum
linktitle: DefaultMetadataProperties
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::DefaultMetadataProperties enum. Enumeration of standard XMP properties in C++.'
type: docs
weight: 4300
url: /cpp/aspose.pdf.facades/defaultmetadataproperties/
---
## DefaultMetadataProperties enum


Enumeration of standard XMP properties.

```cpp
enum class DefaultMetadataProperties
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Advisory | 0 | xmp:Advisory property. An unordered array specifying properties that were edited outside the authoring application. Each item should contain a single /// namespace and XPath separated by one ASCII space |
| BaseURL | 1 | xmp:BaseURL property. The base URL for relative URLs in the document content. If this document contains Internet links, and those links are relative, /// they are relative to this base URL. This property provides a standard way for embedded relative URLs to be interpreted by tools. /// Web authoring tools should set the value based on their notion of where URLs will be interpreted |
| CreateDate | 2 | xmp:CreateDate property. The date and time the resource was originally created. |
| CreatorTool | 3 | xmp:CreatorTool property. The name of the first known tool used to create the resource. |
| Identifier | 4 | xmp:Identifier property. An unordered array of text strings that unambiguously identify the resource within a given context |
| MetadataDate | 5 | xmp:MetadataDate property. The date and time that any metadata for this resource was last changed |
| ModifyDate | 6 | xmp:ModifyDate property. The date and time the resource was last modified. |
| Nickname | 7 | xmp:Nickname property. A short informal name for the resource. |
| Thumbnails | 8 | xmp:Thumbnails property. An alternative array of thumbnail images for a file, which can differ in characteristics such as size or image encoding. |

## See Also

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
