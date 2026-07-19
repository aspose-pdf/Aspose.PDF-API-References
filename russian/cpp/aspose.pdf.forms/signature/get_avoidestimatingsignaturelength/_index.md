---
title: "Метод Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength"
linktitle: "get_AvoidEstimatingSignatureLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength. Получает и устанавливает параметр, определяющий, следует ли избегать оценки длины подписи в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.forms/signature/get_avoidestimatingsignaturelength/
---
## Signature::get_AvoidEstimatingSignatureLength method


Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи.

```cpp
bool Aspose::Pdf::Forms::Signature::get_AvoidEstimatingSignatureLength() const
```

## Примечания


Избегает оценки длины подписи перед подписанием документа. Используется для подписи через [CustomSignHash](../) и через [ExternalSignature](../../externalsignature/). Если [CustomSignHash](../) возвращает подпись длиннее, чем [DefaultSignatureLength](../), будет выброшено исключение [Aspose::Pdf::Security::SignatureLengthMismatchException](../../../aspose.pdf.security/signaturelengthmismatchexception/). Значение по умолчанию — **false**.
## См. также

* Class [Signature](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
