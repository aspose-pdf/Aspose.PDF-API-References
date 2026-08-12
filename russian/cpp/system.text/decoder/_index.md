---
title: "System::Text::Decoder класс"
linktitle: "Декодер"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Text::Decoder класс. Инкапсулирует декодирование последовательности байтов в последовательность символов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.text/decoder/
---
## Decoder class


Инкапсулирует декодирование последовательности байтов в последовательность символов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Decoder : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Преобразует байты в символы. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Преобразует байты в символы. |
| [get_Fallback](./get_fallback/)() const | Получает резервный обработчик ошибок. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Получает резервный буфер. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Получить символы, полученные в результате декодирования буфера. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Получить символы, полученные в результате декодирования буфера. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Получить символы, полученные в результате декодирования буфера. |
| virtual [Reset](./reset/)() | Очищает внутреннее состояние декодера. |
| [set_Fallback](./set_fallback/)(const DecoderFallbackPtr\&) | Устанавливает резервный обработчик ошибок. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
