---
title: Aspose::Pdf::SignaturesCompromiseDetector class
linktitle: SignaturesCompromiseDetector
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SignaturesCompromiseDetector class. Represents a class for checking compromising signatures of the document in C++.'
type: docs
weight: 17100
url: /cpp/aspose.pdf/signaturescompromisedetector/
---
## SignaturesCompromiseDetector class


Represents a class for checking compromising signatures of the document.

```cpp
class SignaturesCompromiseDetector : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Check](./check/)(System::SharedPtr\<Signatures::CompromiseCheckResult\>\&) | Check the digital signatures of the document for compromise. |
| [SignaturesCompromiseDetector](./signaturescompromisedetector/)(System::SharedPtr\<Document\>) | Creates an instance of [SignaturesCompromiseDetector](./) class. |
## Remarks


The detector checks only known ways to compromise signatures. Verification cannot provide a 100% guarantee of the absence of signature compromise and may yield a false negative result for new, unknown compromise methods different from those being tested. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
