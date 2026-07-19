---
title: "Класс System::Text::Encoder"
linktitle: "Encoder"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::Encoder. Инкапсулирует последовательность символов кодировки в последовательность байтов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system.text/encoder/
---
## Encoder class


Инкапсулирует последовательность символов кодировки в последовательность байтов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Encoder : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Преобразует символы в байты. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Преобразует символы в байты. |
| [get_Fallback](./get_fallback/)() const | Получает резервный обработчик ошибок. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Получает резервный буфер. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Получает количество байтов, необходимых для кодирования буфера. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Получает количество байтов, необходимых для кодирования буфера. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Получить байты, полученные в результате кодирования буфера. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Получить байты, полученные в результате кодирования буфера. |
| virtual [Reset](./reset/)() | Очищает внутреннее состояние кодировщика. |
| [set_Fallback](./set_fallback/)(const EncoderFallbackPtr\&) | Устанавливает резервный обработчик ошибок. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
