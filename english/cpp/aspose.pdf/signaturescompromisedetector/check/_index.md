---
title: Aspose::Pdf::SignaturesCompromiseDetector::Check method
linktitle: Check
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SignaturesCompromiseDetector::Check method. Check the digital signatures of the document for compromise in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector::Check method


Check the digital signatures of the document for compromise.

```cpp
bool Aspose::Pdf::SignaturesCompromiseDetector::Check(System::SharedPtr<Signatures::CompromiseCheckResult> &compromiseCheckResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| compromiseCheckResult | System::SharedPtr\<Signatures::CompromiseCheckResult\>\& | The result of verification of the document. |

### ReturnValue

True, if the compromise of the signatures is not detected.
## Remarks



The using of this method for a document in which there are no digital signatures will return **True**. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* Class [SignaturesCompromiseDetector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
