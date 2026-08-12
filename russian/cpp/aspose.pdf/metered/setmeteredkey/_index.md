---
title: "Метод Aspose::Pdf::Metered::SetMeteredKey"
linktitle: "SetMeteredKey"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Metered::SetMeteredKey. Устанавливает публичный и приватный ключ для измеряемой лицензии. Если вы приобрели измеряемую лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переключена в режим оценки; чтобы избежать этого, следует регулярно проверять статус лицензии, и если он находится в режиме оценки, вызвать этот API снова в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Устанавливает публичный и приватный ключ metered. Если вы приобретаете лицензию metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако, если постоянно не удаётся загрузить данные потребления и проходит более 24 часов, лицензия будет переключена в статус оценки; чтобы избежать такой ситуации, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова.

```cpp
void Aspose::Pdf::Metered::SetMeteredKey(const System::String &publicKey, const System::String &privateKey)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | const System::String\& | публичный ключ |
| privateKey | const System::String\& | приватный ключ |

## См. также

* Class [String](../../../system/string/)
* Class [Metered](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
