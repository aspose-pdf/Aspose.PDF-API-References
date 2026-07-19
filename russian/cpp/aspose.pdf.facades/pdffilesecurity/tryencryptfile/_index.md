---
title: "Метод Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile"
linktitle: "TryEncryptFile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile. Шифрует файл Pdf с пользовательским паролем и паролем владельца и устанавливает привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null и пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Не выбрасывает исключение, если процесс завершился с ошибкой в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity::TryEncryptFile method


Шифрует файл [Pdf](../../../aspose.pdf/) с пользовательским паролем и паролем владельца и устанавливает привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null и пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Не выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TryEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |
| keySize | KeySize | [KeySize.x40](../../keysize/) для шифрования 40‑бит, [KeySize.x128](../../keysize/) для шифрования 128‑бит и [KeySize.x256](../../keysize/) для шифрования 256‑бит. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
