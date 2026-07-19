---
title: "Класс System::Text::DecoderExceptionFallbackBuffer"
linktitle: "DecoderExceptionFallbackBuffer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::DecoderExceptionFallbackBuffer. Буфер для стратегии декодирования с выбросом исключений. На самом деле ничего не хранит, а бросает исключения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.text/decoderexceptionfallbackbuffer/
---
## DecoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing decoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderExceptionFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Методы

| Метод | Описание |
| --- | --- |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/)() | Конструктор. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Обрабатывает сбой декодирования. |
| [get_Remaining](./get_remaining/)() const override | Получает количество оставшихся символов. |
| [GetNextChar](./getnextchar/)() override | Получает следующий доступный символ. |
| [MovePrevious](./moveprevious/)() override | Перемещается к предыдущему символу. |
## См. также

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
