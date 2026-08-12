---
title: "System::Globalization::CompareInfo класс"
linktitle: "CompareInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::CompareInfo класс. Выполняет сравнение строк с учётом культуры. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.globalization/compareinfo/
---
## CompareInfo class


Выполняет сравнение строк с учётом культуры. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CompareInfo : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Compare](./compare/)(const String\&, const String\&) const | Сравнивает строки. Не реализовано. |
| virtual [Compare](./compare/)(const String\&, const String\&, CompareOptions) const | Сравнивает строки. Поддерживаются только режимы Ordinal и OrdinalIgnoreCase. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int) const | Сравнивает часть одной строки с частью второй строки. Не реализовано. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int, CompareOptions) const | Сравнивает конечный раздел одной строки с конечным разделом второй строки с использованием методов сравнения строк. Не реализовано. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int) const | Сравнивает конечный раздел одной строки с конечным разделом второй строки. Не реализовано. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int, CompareOptions) const | Сравнивает часть одной строки с частью второй строки с использованием методов сравнения строк. Не реализовано. |
| [CompareInfo](./compareinfo/)(const CompareInfo\&) | Информация RTTI. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LCID](./get_lcid/)() const | Получает LCID культуры, связанной с компаратором. |
| virtual [get_Name](./get_name/)() const | Получает название культуры, связанной с компаратором. |
| [get_Version](./get_version/)() const | Получает информацию о версии сортировки. |
| static [GetCompareInfo](./getcompareinfo/)(int, const SharedPtr\<Reflection::Assembly\>\&) | Получает [CompareInfo](./), связанный с указанной культурой и использующий методы сравнения строк в указанной сборке. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Получает [CompareInfo](./), связанный с указанной культурой и использующий методы сравнения строк в указанной сборке. |
| static [GetCompareInfo](./getcompareinfo/)(int) | Получает [CompareInfo](./), связанный с указанной культурой. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&) | Получает [CompareInfo](./), связанный с указанной культурой. |
| virtual [GetHashCode](./gethashcode/)(const String\&, CompareOptions) const | Получает хеш-код строки на основе указанных параметров сравнения. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [GetSortKey](./getsortkey/)(const String\&, CompareOptions) const | Получает объект [SortKey](../sortkey/) для указанной строки, используя указанные параметры сравнения. |
| virtual [GetSortKey](./getsortkey/)(const String\&) const | Получает объект [SortKey](../sortkey/) для указанной строки. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int) const | Ищет подстроку. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, CompareOptions) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int, CompareOptions) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int, CompareOptions) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int) const | Ищет подстроку. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t) const | Ищет указанный символ. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&) const | Ищет подстроку. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, CompareOptions) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int) const | Ищет указанный символ. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int) const | Ищет указанный символ. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, CompareOptions) const | Ищет подстроку. Поддерживается только режим Ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, CompareOptions) const | Ищет указанный символ. Поддерживается только режим Ordinal. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&, CompareOptions) const | Проверяет, начинается ли указанная строка с указанного префикса, используя указанные параметры сравнения. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&) const | Проверяет, начинается ли указанная строка с указанного префикса. |
| static [IsSortable](./issortable/)(char16_t) | Проверяет, сортируемый ли указанный символ. |
| static [IsSortable](./issortable/)(const String\&) | Проверяет, сортируемая ли указанная строка. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&, CompareOptions) const | Проверяет, заканчивается ли указанная строка указанным суффиксом, используя указанные параметры сравнения. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&) const | Проверяет, заканчивается ли указанная строка указанным суффиксом. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&) const | Ищет последнее вхождение указанной подстроки. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int, CompareOptions) const | Ищет последнее вхождение указанной подстроки, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int, CompareOptions) const | Ищет последнее вхождение указанного символа, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int) const | Ищет последнее вхождение указанной строки. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, CompareOptions) const | Ищет последнее вхождение указанной строки, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, CompareOptions) const | Ищет последнее вхождение указанного символа, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int) const | Ищет последнее вхождение указанной строки. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int) const | Ищет последнее вхождение указанного символа. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, CompareOptions) const | Ищет последнее вхождение указанной строки, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, CompareOptions) const | Ищет последнее вхождение указанного символа, используя указанные параметры сравнения. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t) const | Ищет последнее вхождение указанного символа. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int) const | Ищет последнее вхождение указанного символа. |
| [operator=](./operator=/)(const CompareInfo\&) |  |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
