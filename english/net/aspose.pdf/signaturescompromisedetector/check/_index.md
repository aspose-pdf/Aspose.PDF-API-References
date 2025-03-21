---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector method. Check the digital signatures of the document for compromise
type: docs
weight: 20
url: /net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check method

Check the digital signatures of the document for compromise.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | The result of verification of the document. |

### Return Value

True, if the compromise of the signatures is not detected.

## Remarks

The using of this method for a document in which there are no digital signatures will return `True`.

### See Also

* class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* class [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


