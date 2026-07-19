---
title: "System::Text::ICUEncoder класс"
linktitle: "ICUEncoder"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::ICUEncoder. Кодировщик, использующий ICU для кодирования. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.text/icuencoder/
---
## ICUEncoder class


[Encoder](../encoder/) that uses ICU for encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICUEncoder : public System::Text::Encoder
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Преобразует символы в байты. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Преобразует символы в байты. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Получает количество байтов, необходимых для кодирования буфера. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Получает количество байтов, необходимых для кодирования буфера. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Получить байты, полученные в результате кодирования буфера. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Получить байты, полученные в результате кодирования буфера. |
| [ICUEncoder](./icuencoder/)(ICUEncoding *) | Конструктор. |
| virtual [Reset](./reset/)() | Устанавливает внутренние переменные в исходное состояние. |
| [~ICUEncoder](./~icuencoder/)() | Деструктор. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Base](./base/) | [Base](./base/) тип. |
## См. также

* Class [Encoder](../encoder/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
