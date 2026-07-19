---
title: "System::Text::UnicodeEncoding класс"
linktitle: "UnicodeEncoding"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Text::UnicodeEncoding. Юникодная кодировка. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.text/unicodeencoding/
---
## UnicodeEncoding class


Юникодная кодировка. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонирует объект кодировки. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Сравнивает кодировки. |
| [GetHashCode](./gethashcode/)() const override | Хеширует кодировку. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Получает максимальное количество байт, необходимое для кодирования заданного количества символов. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Получает максимальное количество символов, необходимое для декодирования заданного количества байт. |
| [GetPreamble](./getpreamble/)() override | Возвращает последовательность байтов, обозначающую кодировку (например, BOM). |
| [operator==](./operator==/)(const UnicodeEncoding\&) const | Сравнивает кодировки по номерам кодовых страниц и флагам. |
| [UnicodeEncoding](./unicodeencoding/)() | Конструктор. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool) | Конструктор. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool, bool) | Конструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Номер кодовой страницы в порядке big endian. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Значение кодовой страницы по умолчанию. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Номер кодовой страницы в порядке little endian. |
## См. также

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
