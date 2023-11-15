---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfAOptionClasses.ToUnicodeProcessingRules class. This class describes rules which can be used to solve Adobe Preflight error Text cannot be mapped to Unicode
type: docs
weight: 6100
url: /net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructors

| Name | Description |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Constructor |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Constructor |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Constructor |

## Properties

| Name | Description |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |

### See Also

* namespace [Aspose.Pdf.PdfAOptionClasses](../../aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](../../)


