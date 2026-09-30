---
title: "ToUnicodeProcessingRules Class"
linktitle: "ToUnicodeProcessingRules"
articleTitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.ToUnicodeProcessingRules class. This class describes rules which can be used to solve Adobe Preflight error \"Text cannot be mapped to Unicode\"."
type: docs
weight: 3020
url: "/net/aspose.pdf/tounicodeprocessingrules/"
keywords: "ToUnicodeProcessingRules, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ToUnicodeProcessingRules class

This class describes rules which can be used to solve Adobe Preflight error 
 "Text cannot be mapped to Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructors

| Name | Description |
| --- | --- |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/#constructor)() | Initializes a new instance of the [`ToUnicodeProcessingRules`](../../aspose.pdf/tounicodeprocessingrules/) class. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/#constructor_1)(bool) | Initializes a new instance of the [`ToUnicodeProcessingRules`](../../aspose.pdf/tounicodeprocessingrules/) class with the specified option to remove spaces from CMap names. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/#constructor_2)(bool, bool) | Initializes a new instance of the [`ToUnicodeProcessingRules`](../../aspose.pdf/tounicodeprocessingrules/) class with specified options. |

## Properties

| Name | Description |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](./mapnonlinkedsymbolsonspace/) { get; set; } | Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32). |
| [RemoveSpacesFromCMapNames](./removespacesfromcmapnames/) { get; set; } | Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

