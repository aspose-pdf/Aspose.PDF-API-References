---
title: Aspose::Pdf::Forms::SignHash typedef
linktitle: SignHash
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignHash typedef. Delegate for custom sign the document hash in C++.'
type: docs
weight: 3900
url: /cpp/aspose.pdf.forms/signhash/
---
## SignHash typedef


Delegate for custom sign the document hash.

```cpp
using Aspose::Pdf::Forms::SignHash =  System::MulticastDelegate<System::ArrayPtr<uint8_t>(System::ArrayPtr<uint8_t>, Aspose::Pdf::DigestHashAlgorithm)>
```

## Remarks



[Note](../../aspose.pdf/note/) that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.
## See Also

* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
