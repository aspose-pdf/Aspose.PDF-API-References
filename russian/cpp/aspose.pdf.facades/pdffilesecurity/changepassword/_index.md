---
title: "Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword метод"
linktitle: "ChangePassword"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword метод. Изменяет пользовательский пароль и пароль владельца с помощью пароля владельца, сохраняет исходные настройки безопасности. Новый пользовательский пароль и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца null или пустой. Выбрасывает исключение при неудачном выполнении в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&) method


Изменяет пароль пользователя и пароль владельца, используя пароль владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | const System::String\& | Исходный пароль владельца. |
| newUserPassword | const System::String\& | Новый пароль пользователя. |
| newOwnerPassword | const System::String\& | Новый пароль владельца. |

### ReturnValue

True при успехе.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) method


Изменяет пользовательский пароль и пароль владельца, позволяет сбросить безопасность документа [Pdf](../../../aspose.pdf/). Новый пользовательский пароль и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца null или пустой. Выбрасывает исключение при неудачном выполнении.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | const System::String\& | Исходный пароль владельца. |
| newUserPassword | const System::String\& | Новый пароль пользователя. |
| newOwnerPassword | const System::String\& | Новый пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Сбросить безопасность. |
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
## PdfFileSecurity::ChangePassword(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) method


Изменяет пользовательский пароль и пароль владельца, позволяет сбросить безопасность документа [Pdf](../../../aspose.pdf/). Новый пользовательский пароль и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца null или пустой. Существует 6 возможных комбинаций значений [KeySize](../../keysize/) и [Algorithm](../../algorithm/). Однако комбинации ([KeySize.x40](../../keysize/), [Algorithm.AES](../../algorithm/)) и ([KeySize.x256](../../keysize/), [Algorithm.RC4](../../algorithm/)) недействительны, и соответствующее исключение будет вызвано, если набор обнаружит эту комбинацию. Выбрасывает исключение при неудачном выполнении.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::ChangePassword(const System::String &ownerPassword, const System::String &newUserPassword, const System::String &newOwnerPassword, const System::SharedPtr<DocumentPrivilege> &privilege, KeySize keySize, Algorithm cipher)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | const System::String\& | Исходный пароль владельца. |
| newUserPassword | const System::String\& | Новый пароль пользователя. |
| newOwnerPassword | const System::String\& | Новый пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Сбросить безопасность. |
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
