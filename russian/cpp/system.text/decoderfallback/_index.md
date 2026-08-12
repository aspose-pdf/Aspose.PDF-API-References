---
title: "System::Text::DecoderFallback класс"
linktitle: "DecoderFallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::DecoderFallback класс. Предоставляет API отката для обработки ошибок декодирования. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.text/decoderfallback/
---
## DecoderFallback class


Предоставляет API отката для обработки ошибок декодирования. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DecoderFallback : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Получает буфер, связанный с алгоритмом отката. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Получает реализацию отката по умолчанию для исключений. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Получает максимальное количество символов, которое может вернуть откат. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Получает реализацию отката замены по умолчанию. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Получает стандартную безопасную реализацию отката по умолчанию. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
