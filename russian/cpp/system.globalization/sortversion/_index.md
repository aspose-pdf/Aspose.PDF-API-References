---
title: "Класс System::Globalization::SortVersion"
linktitle: "SortVersion"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Globalization::SortVersion. Предоставляет информацию о версии Unicode, используемой для сравнения и упорядочения строк. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2300
url: /ru/cpp/system.globalization/sortversion/
---
## SortVersion class


Предоставляет информацию о версии Unicode, используемой для сравнения и упорядочения строк. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SortVersion : public System::IEquatable<SharedPtr<SortVersion>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<SortVersion\>) override | Проверяет, равен ли текущий экземпляр [SortVersion](./) указанному объекту [SortVersion](./). |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Проверяет, равен ли текущий экземпляр [SortVersion](./) указанному объекту [SortVersion](./). |
| [get_FullVersion](./get_fullversion/)() | Получает полный номер версии. |
| [get_SortId](./get_sortid/)() | Получает уникальный идентификатор этого объекта. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш-код текущего объекта. |
| [operator!=](./operator!=/)(const SortVersion\&) | Проверяет, не равен ли текущий экземпляр [SortVersion](./) указанному объекту [SortVersion](./). |
| [operator=](./operator=/)(const SortVersion\&) |  |
| [operator==](./operator==/)(const SortVersion\&) | Проверяет, равен ли текущий экземпляр [SortVersion](./) указанному объекту [SortVersion](./). |
| [SortVersion](./sortversion/)(int, const Guid\&) | Информация RTTI. |
| [SortVersion](./sortversion/)(const SortVersion\&) |  |
## См. также

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
