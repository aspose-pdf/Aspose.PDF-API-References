---
title: "System::StringComparer class"
linktitle: "StringComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::StringComparer class. Сравнивает строки, используя различные режимы сравнения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 6200
url: /ru/cpp/system/stringcomparer/
---
## StringComparer class


Сравнивает строки, используя различные режимы сравнения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Сравнивает две строки, используя текущие настройки. |
| static [Create](./create/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) | Создаёт сравниватель, специфичный для культуры. |
| [Equals](./equals/)(String, String) const override | Проверяет, равны ли две строки, используя текущие настройки. |
| static [get_CurrentCulture](./get_currentculture/)() | Одиночка сравнивателя текущей культуры. |
| static [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Одиночка сравнивателя текущей культуры без учёта регистра. |
| static [get_InvariantCulture](./get_invariantculture/)() | Одиночка сравнивателя инвариантной культуры. |
| static [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Одиночка сравнивателя инвариантной культуры без учёта регистра. |
| static [get_Ordinal](./get_ordinal/)() | Одиночка порядкового сравнивателя. |
| static [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Одиночка порядкового сравнивателя без учёта регистра. |
| [GetHashCode](./gethashcode/)(String) const override | Получает хеш‑код строки. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [args_type](./args_type/) | Информация RTTI. |
## См. также

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
