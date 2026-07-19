---
title: "System::Globalization::IdnMapping class"
linktitle: "IdnMapping"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::IdnMapping class. IdnMapping используется для преобразования имён в Punycode. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.globalization/idnmapping/
---
## IdnMapping class


[IdnMapping](./) used to map names to Punycode. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IdnMapping : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Сравнивает два объекта [IdnMapping](./). |
| [get_AllowUnassigned](./get_allowunassigned/)() const | Получает флаг, указывающий, используются ли в операциях непредназначенные кодовые точки. |
| [get_UseStd3AsciiRules](./get_usestd3asciirules/)() const | Получает флаг, указывающий, используются ли в операциях стандартные соглашения об именах. |
| [GetAscii](./getascii/)(const String\&) const | [Convert](../../system/convert/) имя домена Unicode в эквивалент ASCII. |
| [GetAscii](./getascii/)(const String\&, int) const | [Convert](../../system/convert/) имя домена Unicode в эквивалент ASCII. |
| [GetAscii](./getascii/)(const String\&, int, int) const | [Convert](../../system/convert/) имя домена Unicode в эквивалент ASCII. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш-код текущего объекта [IdnMapping](./). |
| [GetUnicode](./getunicode/)(const String\&) const | [Convert](../../system/convert/) имя домена ASCII в эквивалент Unicode. |
| [GetUnicode](./getunicode/)(const String\&, int) const | [Convert](../../system/convert/) имя домена ASCII в эквивалент Unicode. |
| [GetUnicode](./getunicode/)(const String\&, int, int) const | [Convert](../../system/convert/) имя домена ASCII в эквивалент Unicode. |
| [IdnMapping](./idnmapping/)() | Информация RTTI. |
| [IdnMapping](./idnmapping/)(const IdnMapping\&) |  |
| [operator=](./operator=/)(const IdnMapping\&) |  |
| [set_AllowUnassigned](./set_allowunassigned/)(bool) | Устанавливает флаг, указывающий, используются ли в операциях непредназначенные кодовые точки. |
| [set_UseStd3AsciiRules](./set_usestd3asciirules/)(bool) | Устанавливает флаг, указывающий, используются ли в операциях стандартные соглашения об именах. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
