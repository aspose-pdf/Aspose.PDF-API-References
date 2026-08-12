---
title: "Aspose::Pdf::FileChecker::IsContentSafe метод"
linktitle: "IsContentSafe"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::FileChecker::IsContentSafe метод. Проверяет содержимое файлов для выявления опасного контента. При проверке содержимого мы не допускаем добавление опасного контента из текстового файла через поток в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/filechecker/iscontentsafe/
---
## FileChecker::IsContentSafe method


Проверяет содержимое файлов для выявления опасного контента. Путём проверки содержимого мы не допускаем добавление опасного контента из текстового файла через поток.

```cpp
static bool Aspose::Pdf::FileChecker::IsContentSafe(const System::SharedPtr<System::IO::Stream> &stream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток содержимого. |

### ReturnValue

**True** if check passed.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [FileChecker](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
