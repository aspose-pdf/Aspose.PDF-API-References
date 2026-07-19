---
title: "Aspose::Pdf::Forms::ExternalSignature класс"
linktitle: "ExternalSignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::ExternalSignature класс. Создаёт отделённую подпись PKCS#7 с использованием X509Certificate2. Поддерживает usb‑смарткарты, токены без экспортируемых закрытых ключей в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class


Создаёт отдельную подпись PKCS#7 с использованием X509Certificate2. Поддерживает USB‑смарт‑карты, токены без экспортируемых закрытых ключей.

```cpp
class ExternalSignature : public Aspose::Pdf::Forms::Signature
```

## Методы

| Метод | Описание |
| --- | --- |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Создаёт отделённую подпись PKCS#7 **(detached)** с использованием X509Certificate2. Поддерживает usb‑смарткарты, токены без экспортируемых закрытых ключей. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, DigestHashAlgorithm) | Создаёт отделённую подпись PKCS#7 **(detached)** с использованием X509Certificate2. Поддерживает usb‑смарткарты, токены без экспортируемых закрытых ключей. |
| [ExternalSignature](./externalsignature/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, bool) | Создаёт отдельную подпись PKCS#7 с использованием X509Certificate2. Поддерживает USB‑смарт‑карты, токены без экспортируемых закрытых ключей. |
| [ExternalSignature](./externalsignature/)(const System::String\&, bool) | Создаёт подпись PKCS#7 с использованием X509Certificate2 в виде строки base64. |
| [ExternalSignature](./externalsignature/)(const System::String\&, DigestHashAlgorithm) | Создаёт подпись PKCS#7 **(detached)** с использованием X509Certificate2 в виде строки base64. |
## См. также

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
