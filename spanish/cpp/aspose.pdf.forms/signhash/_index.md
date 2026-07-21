---
title: "Aspose::Pdf::Forms::SignHash typedef"
linktitle: "SignHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::SignHash typedef. Delegado para firmar de forma personalizada el hash del documento en C++."
type: docs
weight: 3900
url: /es/cpp/aspose.pdf.forms/signhash/
---
## SignHash typedef


Delegado para firmar de forma personalizada el hash del documento.

```cpp
using Aspose::Pdf::Forms::SignHash =  System::MulticastDelegate<System::ArrayPtr<uint8_t>(const System::ArrayPtr<uint8_t>&, Aspose::Pdf::DigestHashAlgorithm)>
```

## Observaciones



[Note](../../aspose.pdf/note/) that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.
## Ver también

* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
