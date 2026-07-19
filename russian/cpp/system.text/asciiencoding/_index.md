---
title: "Класс System::Text::ASCIIEncoding"
linktitle: "ASCIIEncoding"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::ASCIIEncoding. Представляет кодировку ASCII. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.text/asciiencoding/
---
## ASCIIEncoding class


Представляет кодировку ASCII. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Методы

| Метод | Описание |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/)() | Конструктор. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Получает максимальное количество байтов, необходимое для хранения строки известной длины в символах. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Получает максимальное количество символов, необходимое для декодирования заданного количества байт. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Значение кодовой страницы по умолчанию. |
## См. также

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
