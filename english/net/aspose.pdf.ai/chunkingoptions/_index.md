---
title: "ChunkingOptions Class"
linktitle: "ChunkingOptions"
articleTitle: "ChunkingOptions"
second_title: "Aspose.PDF for .NET"
description: "Configuration options for document chunking operations."
type: docs
weight: 190
url: "/net/aspose.pdf.ai/chunkingoptions/"
keywords: "ChunkingOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ChunkingOptions class

Configuration options for document chunking operations.

```csharp
public sealed class ChunkingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ChunkingOptions](./chunkingoptions/#constructor) | Initializes a new instance of the ChunkingOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [MaxChunkSize](./maxchunksize/) { get; set; } | Gets or sets the maximum size of each chunk in tokens. |
| [OverlapSize](./overlapsize/) { get; set; } | Gets or sets the number of tokens to overlap between consecutive chunks. |

## Methods

| Name | Description |
| --- | --- |
| [Validate](./validate/) | Validates the current options configuration. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultMaxChunkSize](./defaultmaxchunksize/) | The default maximum chunk size in tokens. |
| const [DefaultOverlapSize](./defaultoverlapsize/) | The default overlap size in tokens between consecutive chunks. |
| const [MaximumChunkSize](./maximumchunksize/) | The maximum allowed chunk size. |
| const [MinimumChunkSize](./minimumchunksize/) | The minimum allowed chunk size. |

## Remarks

This class provides configuration for controlling how documents
 are split into chunks suitable for AI processing and embeddings.

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

