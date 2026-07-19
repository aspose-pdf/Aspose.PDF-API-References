---
title: "Класс System::EnumValues"
linktitle: "EnumValues"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::EnumValues. Предоставляет метаинформацию о константах перечисления типа enum E в C++."
type: docs
weight: 2400
url: /ru/cpp/system/enumvalues/
---
## EnumValues class


Предоставляет метаинформацию о константах перечисления типа **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


| Параметр | Описание |
| --- | --- |
| E | Тип перечисления |
## Методы

| Метод | Описание |
| --- | --- |
| [EnumValues](./enumvalues/)() | Создаёт экземпляр. |
| [GetNames](./getnames/)() const override | Возвращает массив, содержащий все имена перечисления **E**. |
| static [GetNames](../enumvaluesbase/getnames/)(const TypeInfo\&) | Получает массив имён констант в указанном перечислении. |
| [GetUnderlyingType](./getunderlyingtype/)() const override | Возвращает базовый тип указанного перечисления. |
| static [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const TypeInfo\&) | Возвращает базовый тип указанного перечисления. |
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Возвращает упакованное значение константы перечисления с указанным именем. |
| [GetValueOf](./getvalueof/)(long) const override | Возвращает упакованное значение константы перечисления с указанным значением. |
| [GetValues](./getvalues/)() const override | Возвращает массив, содержащий все значения перечисления **E**. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Возвращает массив, содержащий все значения указанного типа перечисления. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Возвращает объект, представляющий значение константы перечисления указанного типа с указанным именем. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, uint64_t) | Преобразует указанное 64‑битное беззнаковое целое значение в член перечисления. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Преобразует указанный объект с целочисленным значением в член перечисления. |
| virtual [~EnumValues](./~enumvalues/)() | Деструктор. |

## См. также

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
