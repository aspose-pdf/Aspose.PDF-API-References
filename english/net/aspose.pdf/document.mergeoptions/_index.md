---
title: Class Document.MergeOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocumentMergeOptions class. Represents the options to Merge methods
type: docs
weight: 3990
url: /net/aspose.pdf/document.mergeoptions/
---
## Document.MergeOptions class

Represents the options to Merge methods.

```csharp
public class MergeOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MergeOptions](../../aspose.pdf/document.mergeoptions/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConcatenationPacketSize](../../aspose.pdf/document.mergeoptions/concatenationpacketsize) { get; set; } | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. The default value is 4. |
| [IsNeedPageTreeBalance](../../aspose.pdf/document.mergeoptions/isneedpagetreebalance) { get; set; } | Gets and sets the requirement for page tree balancing The entire page tree in the resulting document will be rebalanced. It creates balanced pages tree to speed up pages access. |
| [MaximumNodesInLevel](../../aspose.pdf/document.mergeoptions/maximumnodesinlevel) { get; set; } | Gets and sets the maximum nodes in pages tree level. Default is 10. |
| [UseDiskBuffer](../../aspose.pdf/document.mergeoptions/usediskbuffer) { get; set; } | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. The default value is `false`. |

### See Also

* class [Document](../document/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


