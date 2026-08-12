---
title: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege method"
linktitle: "TrySetPrivilege"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege method. Устанавливает безопасность PDF‑файла с оригинальным паролем. Не выбрасывает исключение, если процесс завершился с ошибкой в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity::TrySetPrivilege method


Устанавливает безопасность [Pdf](../../../aspose.pdf/) файла с оригинальным паролем. Не выбрасывает исключение, если процесс завершился с ошибкой.

```cpp
bool Aspose::Pdf::Facades::PdfFileSecurity::TrySetPrivilege(const System::String &userPassword, const System::String &ownerPassword, const System::SharedPtr<DocumentPrivilege> &privilege)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | const System::String\& | Исходный пароль пользователя. |
| ownerPassword | const System::String\& | Исходный пароль владельца. |
| привилегия | const System::SharedPtr\<DocumentPrivilege\>\& | Установить привилегию. |

### ReturnValue

True при успехе, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentPrivilege](../../documentprivilege/)
* Class [PdfFileSecurity](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
