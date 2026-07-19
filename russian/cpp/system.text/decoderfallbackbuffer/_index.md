---
title: "System::Text::DecoderFallbackBuffer класс"
linktitle: "DecoderFallbackBuffer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::DecoderFallbackBuffer класс. Предоставляет буфер для реализации отката. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.text/decoderfallbackbuffer/
---
## DecoderFallbackBuffer class


Предоставляет буфер для реализации отката. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DecoderFallbackBuffer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) | Реализует фактическую процедуру отката. |
| virtual [get_Remaining](./get_remaining/)() const | Получает оставшееся количество символов для обработки. |
| virtual [GetNextChar](./getnextchar/)() | Извлекает следующий символ из буфера отката. |
| virtual [MovePrevious](./moveprevious/)() | Перемещает позицию буфера на один шаг назад, если это возможно. |
| virtual [Reset](./reset/)() | Сбрасывает буфер в исходное состояние. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
