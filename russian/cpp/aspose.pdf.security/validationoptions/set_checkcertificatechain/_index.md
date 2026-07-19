---
title: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain method"
linktitle: "set_CheckCertificateChain"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain method. Устанавливает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.security/validationoptions/set_checkcertificatechain/
---
## ValidationOptions::set_CheckCertificateChain method


Устанавливает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки.

```cpp
void Aspose::Pdf::Security::ValidationOptions::set_CheckCertificateChain(bool value)
```

## Примечания


Когда свойство установлено, будет проверяться наличие цепочки сертификатов; если её нет, результат проверки будет [ValidationStatus::Undefined](../../validationstatus/), что соответствует поведению Adobe Acrobat. Если вы хотите только онлайн‑проверять статус отзыва, установите поле в **false**. Значение по умолчанию — **false**.
## См. также

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
