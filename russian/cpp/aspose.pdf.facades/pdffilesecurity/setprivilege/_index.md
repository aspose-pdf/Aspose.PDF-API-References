---
title: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege метод"
linktitle: "SetPrivilege"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege метод. Устанавливает безопасность Pdf файла с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выбрасывает исключение, если процесс завершился с ошибкой в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## PdfFileSecurity::SetPrivilege(const System::SharedPtr\<DocumentPrivilege\>\&) method


Устанавливает безопасность файла [Pdf](../../../aspose.pdf/) с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |

### ReturnValue

True при успехе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSecurity::SetPrivilege(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) method


Устанавливает безопасность файла [Pdf](../../../aspose.pdf/) с оригинальным паролем. Выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::SetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Исходный пароль пользователя. |
| ownerPassword | const System::String\& | Исходный пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |

### ReturnValue

True при успехе.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
