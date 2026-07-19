---
title: "Класс System::Text::ICUDecoder"
linktitle: "ICUDecoder"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::ICUDecoder. Декодер, использующий ICU для декодирования. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2000
url: /ru/cpp/system.text/icudecoder/
---
## ICUDecoder class


[Decoder](../decoder/) that uses ICU for decoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUDecoder : public System::Text::Decoder
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Преобразует байты в символы. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Преобразует байты в символы. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Получает количество символов, необходимых для декодирования буфера. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Получить символы, полученные в результате декодирования буфера. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Получить символы, полученные в результате декодирования буфера. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Получить символы, полученные в результате декодирования буфера. |
| [ICUDecoder](./icudecoder/)(ICUEncoding *) | Конструктор. |
| virtual [Reset](./reset/)() | Устанавливает внутренние переменные в исходное состояние. |
| virtual [~ICUDecoder](./~icudecoder/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Base](./base/) | [Base](./base/) тип. |
## См. также

* Class [Decoder](../decoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
