---
title: "System::Text::EncoderReplacementFallbackBuffer класс"
linktitle: "EncoderReplacementFallbackBuffer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::EncoderReplacementFallbackBuffer. Буфер для замены стратегии fallback кодирования. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.text/encoderreplacementfallbackbuffer/
---
## EncoderReplacementFallbackBuffer class


[Buffer](../../system/buffer/) for replacing encoding fallback strategy. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderReplacementFallbackBuffer : public System::Text::EncoderFallbackBuffer
```

## Методы

| Метод | Описание |
| --- | --- |
| [EncoderReplacementFallbackBuffer](./encoderreplacementfallbackbuffer/)(const EncoderReplacementFallbackPtr\&) | Конструктор. |
| [Fallback](./fallback/)(char_t, int) override | Обрабатывает сбой кодирования. |
| [Fallback](./fallback/)(char_t, char_t, int) override | Обрабатывает сбой кодирования. |
| [get_Remaining](./get_remaining/)() const override | Получает количество оставшихся символов в буфере. |
| [GetNextChar](./getnextchar/)() override | Получает следующий доступный символ. |
| [MovePrevious](./moveprevious/)() override | Перемещается к предыдущему символу. |
| [Reset](./reset/)() override | Сбрасывает буфер в исходное состояние (до вызова [Fallback()](./fallback/)). |
## См. также

* Class [EncoderFallbackBuffer](../encoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
