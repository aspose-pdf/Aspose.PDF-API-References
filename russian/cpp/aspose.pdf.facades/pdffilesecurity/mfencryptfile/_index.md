---
title: "Метод Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile"
linktitle: "MfEncryptFile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile. Шифрует файл Pdf с пользовательским паролем и паролем владельца и устанавливает привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Выбрасывает исключение, если процесс завершился с ошибкой в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/mfencryptfile/
---
## PdfFileSecurity::MfEncryptFile(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) method


Шифрует файл [Pdf](../../../aspose.pdf/) с пользовательским паролем и паролем владельца и устанавливает привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |
| keySize | KeySize | [KeySize.x40](../../keysize/) для шифрования 40‑бит, [KeySize.x128](../../keysize/) для шифрования 128‑бит и [KeySize.x256](../../keysize/) для шифрования 256‑бит. |

### ReturnValue

True при успехе.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::MfEncryptFile(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) method


Шифрует файл [Pdf](../../../aspose.pdf/) с пользовательским паролем и паролем владельца и устанавливает привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Существует 6 возможных комбинаций значений [KeySize](../../keysize/) и [Algorithm](../../algorithm/). Однако комбинации ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) и ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) недействительны, и соответствующее исключение будет вызвано, если система встретит эту комбинацию. Выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::MfEncryptFile(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize, Algorithm cipher)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Пароль пользователя. |
| ownerPassword | const System::String\& | Пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |
| keySize | KeySize | [KeySize.x40](../../keysize/) для шифрования 40‑бит, [KeySize.x128](../../keysize/) для шифрования 128‑бит и [KeySize.x256](../../keysize/) для шифрования 256‑бит. |
| cipher | Algorithm | [Algorithm.AES](../../algorithm/) для шифрования с использованием алгоритма AES или [Algorithm.RC4](../../algorithm/) для шифрования RC4. |

### ReturnValue

True при успехе.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Enum [KeySize](../../keysize/)
* Enum [Algorithm](../../algorithm/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
