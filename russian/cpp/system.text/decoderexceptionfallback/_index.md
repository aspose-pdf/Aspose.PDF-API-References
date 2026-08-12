---
title: "System::Text::DecoderExceptionFallback класс"
linktitle: "DecoderExceptionFallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::DecoderExceptionFallback класс. Предоставляет стратегию отката, бросающую исключения. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.text/decoderexceptionfallback/
---
## DecoderExceptionFallback class


Предоставляет стратегию отката, бросающую исключения. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DecoderExceptionFallback : public System::Text::DecoderFallback
```

## Методы

| Метод | Описание |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Создаёт буфер отката. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Получает максимальное количество символов, которое может вернуть экземпляр. |
## См. также

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
