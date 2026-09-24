---
title: "LoadOptions.ResourceLoadingResult Class"
linktitle: "LoadOptions.ResourceLoadingResult"
articleTitle: "LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF for .NET"
description: "Result of custom loading of resource"
type: docs
weight: 1820
url: "/net/aspose.pdf/loadoptions.resourceloadingresult/"
keywords: "LoadOptions.ResourceLoadingResult, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## LoadOptions.ResourceLoadingResult class

Result of custom loading of resource

```csharp
public class ResourceLoadingResult
```

## Constructors

| Name | Description |
| --- | --- |
| [LoadOptions.ResourceLoadingResult](./resourceloadingresult/#constructor)(*byte[]*) | Creates instance of loading result. |

## Properties

| Name | Description |
| --- | --- |
| [Data](./data/) { get; } | Bynary data that loaded with custom loader - it must be set after loading. |

## Fields

| Name | Description |
| --- | --- |
| [EncodingIfKnown](./encodingifknown/) | Sometimes encoding of resource is known after or during loading. |
| [ExceptionOfLoadingIfAny](./exceptionofloadingifany/) | Sometimes it's impossible to load requested resource for some reason. |
| [LoadingCancelled](./loadingcancelled/) | Sometimes for some reasons loading should not occure custom code. In such case. |
| [MIMETypeIfKnown](./mimetypeifknown/) | Sometimes knowledge about MIME type of loaded resource is usefull for converter. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

