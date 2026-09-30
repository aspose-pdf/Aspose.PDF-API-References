---
title: "RunCreateRequest.MaxCompletionTokens"
linktitle: "MaxCompletionTokens"
articleTitle: "MaxCompletionTokens"
second_title: "Aspose.PDF for .NET API Reference"
description: "RunCreateRequest property. Gets or sets the maximum number of completion tokens that may be used over the course of the run. The run will make a best effort ..."
type: docs
weight: 130
url: "/net/aspose.pdf.ai/runcreaterequest/maxcompletiontokens/"
product_version: "26.9.0"
---
## RunCreateRequest.MaxCompletionTokens property

Gets or sets the maximum number of completion tokens that may be used over the course of the run.
 The run will make a best effort to use only the number of completion tokens specified, across multiple turns of the run.
 If the run exceeds the number of completion tokens specified, the run will end with status incomplete. See incomplete_details for more info.

```csharp
public int? MaxCompletionTokens { get; set; }
```

### See Also

* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

