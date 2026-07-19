---
title: "Aspose::Pdf::Forms::SignHash typedef"
linktitle: "SignHash"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::SignHash typedef. Делегат для пользовательской подписи хеша документа в C++."
type: docs
weight: 3900
url: /ru/cpp/aspose.pdf.forms/signhash/
---
## SignHash typedef


Делегат для пользовательской подписи хэша документа.

```cpp
using Aspose::Pdf::Forms::SignHash =  System::MulticastDelegate<System::ArrayPtr<uint8_t>(const System::ArrayPtr<uint8_t>&, Aspose::Pdf::DigestHashAlgorithm)>
```

## Примечания



[Note](../../aspose.pdf/note/) that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.
## См. также

* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
