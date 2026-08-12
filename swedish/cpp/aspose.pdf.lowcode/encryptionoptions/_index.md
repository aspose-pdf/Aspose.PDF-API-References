---
title: "Aspose::Pdf::LowCode::EncryptionOptions-klass"
linktitle: "EncryptionOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::EncryptionOptions-klass. Representerar krypteringsalternativ för Security‑plugin i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.lowcode/encryptionoptions/
---
## EncryptionOptions class


Representerar krypteringsalternativ för [Security](../security/)-plugin.

```cpp
class EncryptionOptions : public Aspose::Pdf::LowCode::OrganizerBaseOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncryptionOptions](./encryptionoptions/)(const System::String\&, const System::String\&, const System::SharedPtr\<Aspose::Pdf::Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm) | Initierar en ny instans av [EncryptionOptions](./)-objektet med standardalternativ. |
| [get_CryptoAlgorithm](./get_cryptoalgorithm/)() const | Kryptografisk algoritm, se [CryptoAlgorithm](../../aspose.pdf/cryptoalgorithm/) för detaljer. |
| [get_DocumentPrivilege](./get_documentprivilege/)() const | [Document](../../aspose.pdf/document/)-behörigheter, se [Permissions](../../aspose.pdf/permissions/) för detaljer. |
| [get_OwnerPassword](./get_ownerpassword/)() const | Ägarlösenord. |
| [get_UserPassword](./get_userpassword/)() const | Användarlösenord. |
| [set_CryptoAlgorithm](./set_cryptoalgorithm/)(Aspose::Pdf::CryptoAlgorithm) | Kryptografisk algoritm, se [CryptoAlgorithm](../../aspose.pdf/cryptoalgorithm/) för detaljer. |
| [set_DocumentPrivilege](./set_documentprivilege/)(const System::SharedPtr\<Aspose::Pdf::Facades::DocumentPrivilege\>\&) | [Document](../../aspose.pdf/document/)-behörigheter, se [Permissions](../../aspose.pdf/permissions/) för detaljer. |
| [set_OwnerPassword](./set_ownerpassword/)(const System::String\&) | Ägarlösenord. |
| [set_UserPassword](./set_userpassword/)(const System::String\&) | Användarlösenord. |
## Se även

* Class [OrganizerBaseOptions](../organizerbaseoptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
