---
title: "System::EnumValuesBase класс"
linktitle: "EnumValuesBase"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::EnumValuesBase class. Базовый класс для класса, представляющего метаинформацию типа перечисления в C++."
type: docs
weight: 2500
url: /ru/cpp/system/enumvaluesbase/
---
## EnumValuesBase class


Базовый класс для класса, представляющего метаинформацию типа перечисления.

```cpp
class EnumValuesBase
```

## Методы

| Метод | Описание |
| --- | --- |
| static [GetNames](./getnames/)(const TypeInfo\&) | Получает массив имён констант в указанном перечислении. |
| static [GetUnderlyingType](./getunderlyingtype/)(const TypeInfo\&) | Возвращает базовый тип указанного перечисления. |
| static [GetValues](./getvalues/)(const TypeInfo\&) | Возвращает массив, содержащий все значения указанного типа перечисления. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Возвращает объект, представляющий значение константы перечисления указанного типа с указанным именем. |
| static [ToObject](./toobject/)(const TypeInfo\&, uint64_t) | Преобразует указанное 64‑битное беззнаковое целое значение в член перечисления. |
| static [ToObject](./toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Преобразует указанный объект с целочисленным значением в член перечисления. |
## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
