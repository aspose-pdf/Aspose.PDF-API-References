---
title: "Класс System::ObjectExt"
linktitle: "ObjectExt"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::ObjectExt. Предоставляет статические методы, имитирующие методы C# Object, вызываемые для не-Object типов C++ (строки, числа и т.д.). Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры каким-либо способом в C++."
type: docs
weight: 5100
url: /ru/cpp/system/objectext/
---
## ObjectExt class


Предоставляет статические методы, имитирующие методы C# [Object](../object/), вызываемые для не-Object типов C++ (строки, числа и т.д.). Это статический тип без сервисов экземпляров. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class ObjectExt : public System::ObjectType
```

## Методы

| Метод | Описание |
| --- | --- |
| static [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Преобразует фундаментальные значения массивов (что C# делает неявно, а C++ очевидно не делает). |
| static [Box](./box/)(const T\&) | Упаковывает типы-значения для преобразования в [Object](../object/). Реализация для enum-типов. |
| static [Box](./box/)(const T\&) | Упаковывает типы-значения для преобразования в [Object](../object/). Реализация для не-enum типов. |
| static [Box](./box/)(const T\&) | Упаковывает типы [Nullable](../nullable/) для преобразования в [Object](../object/). |
| static [Box](./box/)(const String\&) | Упаковывает строковые значения. |
| static [BoxEnum](./boxenum/)(T) | Упаковывает enum-типы для передачи в виде [Object](../object/). |
| static [CastToIList](./casttoilist/)(const SmartPtr\<Object\>\&) |  |
| static [Coalesce](./coalesce/)(T0, T1) | Реализация трансляции оператора '??' для типов, не допускающих null. |
| static [Coalesce](./coalesce/)(System::Nullable\<T0\>, T1) | Реализация трансляции оператора '??' для nullable типов. |
| static [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Реализация перевода оператора '??='. |
| static [CoalesceInternal](./coalesceinternal/)(RT1, F) | Реализация перевода оператора '??' для типов, не допускающих null. Перегрузка для случая, когда RT2 преобразуем к RT1. |
| static [Equals](./equals/)(const T\&, const T2\&) |  |
| static [Equals](./equals/)(const T\&, const T2\&) | Подстановка вызовов C# [Object.Equals](../object/equals/) работающая для любого типа в C++. Перегрузка для типов умных указателей. |
| static [Equals](./equals/)(T, const T2\&) | Подстановка вызовов C# [Object.Equals](../object/equals/) работающая для любого типа в C++. Перегрузка для структурных типов. |
| static [Equals](./equals/)(const T\&, const T2\&) | Подстановка вызовов C# [Object.Equals](../object/equals/) работающая для любого типа в C++. Перегрузка для скалярных типов. |
| static [Equals](./equals/)(const char_t(&), String) | Подстановка вызовов C# [Object.Equals](../object/equals/) работающая для любого типа в C++. Перегрузка для строковых литералов со сравнением строк. |
| static [Equals](./equals/)(const float\&, const float\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static [Equals](./equals/)(const double\&, const double\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [GetHashCode](./gethashcode/)(const T\&) | Реализует вызовы [GetHashCode()](./gethashcode/); работает как с подклассами [Object](../object/), так и с несвязанными типами. |
| static [Is](./is/)(const T\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых (значимых) типов, что именно они и есть. |
| static [Is](./is/)(const U\&) | Реализует перевод оператора 'is'. Специализация для типов указателей, оптимизированных для классов 'final'. |
| static [Is](./is/)(const U\&) | Реализует перевод оператора 'is'. Специализация для типов указателей. |
| static [Is](./is/)(const Object\&) | Реализует перевод оператора 'is'. Специализация для значимых типов. |
| static [Is](./is/)(const Object\&) | Реализует перевод оператора 'is'. Специализация для непреобразуемых типов. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Реализует перевод оператора 'is'. Специализация для типов указателей. |
| static [Is](./is/)(const ExceptionWrapper\<U\>\&) | Реализует перевод оператора 'is'. Специализация для типов-обёрток исключений. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Реализует перевод оператора 'is'. Специализация для nullable‑типов. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых типов с определённым оператором ==. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых типов без определённого оператора ==. |
| static [Is](./is/)(const SmartPtr\<V\>\&) | Реализует перевод оператора 'is'. Специализация для значимых типов, упакованных в интерфейсы. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Реализует перевод оператора 'is'. Специализация для enum‑типов. |
| static [Is](./is/)(const WeakPtr\<U\>\&) | Реализует перевод оператора 'is'. Специализация для enum‑типов против слабых указателей. |
| static [Is](./is/)(const Nullable\<U\>\&) | Реализует перевод оператора 'is'. Специализация для типа [Nullable](../nullable/). |
| static [Is](./is/)(const char16_t *) | Реализует перевод оператора 'is'. Специализация для строкового литерала. |
| static [Is](./is/)(int32_t) | Реализует перевод оператора 'is'. Специализация для целочисленного литерала. |
| static [IsBoxedValue](./isboxedvalue/)(const SmartPtr\<Object\>\&) | Проверяет, является ли объект упакованным значением. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Преобразует [Object](../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с bpxed‑значением. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Преобразует [Object](../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением. |
| static [ToString](./tostring/)(const char_t *) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(const Nullable\<T\>\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(const T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(const T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(T\&&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(const T\&) | Замена метода C# ToString для работы с любым типом C++. |
| static [ToString](./tostring/)(T\&&) | Замена метода C# ToString для работы с любым типом C++. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Разупаковывает типы-значения после преобразования в [Object](../object/). Реализация для перечислений. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Разупаковывает типы-значения после преобразования в [Object](../object/). Реализация для не‑перечислений и типов, не допускающих null. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Разупаковывает типы-значения после преобразования в [Object](../object/). Реализация для не‑перечислений и типов, не допускающих null. |
| static [Unbox](./unbox/)(E) | Разупаковывает типы перечислений в целое число. |
| static [Unbox](./unbox/)(E) | Преобразует типы перечислений. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Разупаковывает строковые значения. |
| static [UnboxStringSafe](./unboxstringsafe/)(const SmartPtr\<Object\>\&) | Разупаковывает строку из упакованного значения. |
| static [UnboxToNullable](./unboxtonullable/)(const SmartPtr\<Object\>\&, bool) | Разупаковывает объект в тип, допускающий null. |
| static [UnknownIsNull](./unknownisnull/)(T) | Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для не‑скалярных типов. |
| static [UnknownIsNull](./unknownisnull/)(T) | Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для скалярных типов. |
| static [UnknownToObject](./unknowntoobject/)(T) | Преобразует неизвестный тип в [Object](../object/), обрабатывая как типы умных указателей, так и типы значений. |
| static [UnknownToObject](./unknowntoobject/)(const T\&) | Преобразует неизвестный тип в [Object](../object/), обрабатывая как типы умных указателей, так и типы значений. |
## См. также

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
