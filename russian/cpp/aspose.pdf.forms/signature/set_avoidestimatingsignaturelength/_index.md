---
title: "Метод Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength"
linktitle: "set_AvoidEstimatingSignatureLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength. Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.forms/signature/set_avoidestimatingsignaturelength/
---
## Signature::set_AvoidEstimatingSignatureLength method


Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи.

```cpp
void Aspose::Pdf::Forms::Signature::set_AvoidEstimatingSignatureLength(bool value)
```

## Примечания


Избегает оценки длины подписи перед подписанием документа. Используется для подписи через [CustomSignHash](../) и через [ExternalSignature](../../externalsignature/). Если [CustomSignHash](../) возвращает подпись длиннее, чем [DefaultSignatureLength](../), будет выброшено исключение [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/). Значение по умолчанию — **false**.
## См. также

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
