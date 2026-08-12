---
title: "Класс System::Version"
linktitle: "Версия"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Version. Представляет номер версии. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 7600
url: /ru/cpp/system/version/
---
## Version class


Представляет номер версии. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Version
```

## Методы

| Метод | Описание |
| --- | --- |
| [CompareTo](./compareto/)(const Version\&) const | Сравнивает версии, представленные текущим объектом и указанным объектом. |
| [Equals](./equals/)(const Version\&) const | Определяет, равны ли номера версий, представленные текущим и указанным объектами. |
| [get_Build](./get_build/)() const | Возвращает номер сборки. |
| [get_Major](./get_major/)() const | Возвращает основной номер версии. |
| [get_MajorRevision](./get_majorrevision/)() const | Возвращает старшее 16‑битное значение номера ревизии. |
| [get_Minor](./get_minor/)() const | Возвращает младший номер версии. |
| [get_MinorRevision](./get_minorrevision/)() const | Возвращает младшее 16‑битное значение номера ревизии. |
| [get_Revision](./get_revision/)() const | Возвращает номер ревизии. |
| [GetHashCode](./gethashcode/)() const | Возвращает хеш‑код для текущего объекта. |
| static [Parse](./parse/)(const String\&) | Преобразует строковое представление номера версии в эквивалентный экземпляр класса [Version](./). |
| [ToString](./tostring/)() const | Возвращает строковое представление номера версии, представленного текущим объектом. |
| [ToString](./tostring/)(int) const | Возвращает строковое представление указанного количества секций номера версии, представленного текущим объектом. |
| [Version](./version/)(int, int, int, int) | Создаёт экземпляр, представляющий указанные значения major, minor, build и revision. |
| [Version](./version/)(int, int, int) | Создаёт экземпляр, представляющий указанные значения major, minor и build. |
| [Version](./version/)(int, int) | Создаёт экземпляр, представляющий указанные значения major и values. |
| [Version](./version/)(const String\&) | Создаёт экземпляр, представляющий номер версии, представленный в виде строки. |
| [Version](./version/)() | Создаёт экземпляр, представляющий номер версии 0.0.-1.-1. |
## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
