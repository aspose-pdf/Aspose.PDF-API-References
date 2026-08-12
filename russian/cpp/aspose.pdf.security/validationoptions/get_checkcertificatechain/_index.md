---
title: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain method"
linktitle: "get_CheckCertificateChain"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain method. Получает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.security/validationoptions/get_checkcertificatechain/
---
## ValidationOptions::get_CheckCertificateChain method


Возвращает значение, указывающее, следует ли проверять цепочку сертификатов во время процесса проверки.

```cpp
bool Aspose::Pdf::Security::ValidationOptions::get_CheckCertificateChain() const
```

## Примечания


Когда свойство установлено, будет проверяться наличие цепочки сертификатов; если её нет, результат проверки будет [ValidationStatus::Undefined](../../validationstatus/), что соответствует поведению Adobe Acrobat. Если вы хотите только онлайн‑проверять статус отзыва, установите поле в **false**. Значение по умолчанию — **false**.
## См. также

* Class [ValidationOptions](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
