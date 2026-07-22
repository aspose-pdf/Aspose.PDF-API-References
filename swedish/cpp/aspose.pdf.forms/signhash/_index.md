---
title: "Aspose::Pdf::Forms::SignHash typedef"
linktitle: "SignHash"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::SignHash typedef. Delegat för anpassad signering av dokumenthashen i C++."
type: docs
weight: 3900
url: /sv/cpp/aspose.pdf.forms/signhash/
---
## SignHash typedef


Delegat för att anpassa signering av dokumenthashen.

```cpp
using Aspose::Pdf::Forms::SignHash =  System::MulticastDelegate<System::ArrayPtr<uint8_t>(const System::ArrayPtr<uint8_t>&, Aspose::Pdf::DigestHashAlgorithm)>
```

## Anmärkningar



[Note](../../aspose.pdf/note/) that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.
## Se även

* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
