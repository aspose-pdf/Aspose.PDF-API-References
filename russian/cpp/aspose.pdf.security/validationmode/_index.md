---
title: "Aspose::Pdf::Security::ValidationMode enum"
linktitle: "ValidationMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Security::ValidationMode enum. Указывает режим проверки для процессов проверки подписи PDF в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.security/validationmode/
---
## ValidationMode enum


Указывает режим проверки для процессов проверки подписи PDF.

```cpp
enum class ValidationMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Представляет режим, при котором проверка не выполняется. |
| OnlyCheck | 1 | Представляет режим, при котором проверка выполняется, но её результат не влияет на проверку цифровой подписи. Вы можете проверить результат проверки самостоятельно. |
| Strict | 2 | Представляет режим, при котором проверка выполняется, и её результат влияет на проверку цифровой подписи. Если сертификат не может быть проверен, цифровая подпись будет считаться недействительной. Вы можете проверить результат проверки самостоятельно. |

## См. также

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
