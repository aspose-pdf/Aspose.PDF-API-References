---
title: "System::Text::EncoderFallback класс"
linktitle: "EncoderFallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::EncoderFallback класс. Предоставляет API отката для обработки ошибок кодирования. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.text/encoderfallback/
---
## EncoderFallback class


Предоставляет API отката для обработки ошибок кодирования. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class EncoderFallback : public System::Object
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
