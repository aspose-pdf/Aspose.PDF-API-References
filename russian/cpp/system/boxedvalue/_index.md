---
title: "класс System::BoxedValue"
linktitle: "BoxedValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::BoxedValue класс. Представляет упакованное значение. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 900
url: /ru/cpp/system/boxedvalue/
---
## BoxedValue class


Представляет упакованное значение. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```


| Параметр | Описание |
| --- | --- |
| T | Тип упакованного значения, представленного классом |
## Методы

| Метод | Описание |
| --- | --- |
| [BoxedValue](./boxedvalue/)(const T\&) | Создаёт объект, представляющий указанное упакованное значение. |
| [Equals](./equals/)(ptr) override | Определяет равенство упакованных значений, представленных текущим и указанным объектами. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш‑код для текущего объекта. |
| [GetType](./gettype/)() const override | Получает фактический тип объекта. |
| [GetTypeCode](./gettypecode/)() const override | Возвращает значение, представляющее тип упакованного значения, представленного текущим объектом. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Возвращает числовое значение упакованного объекта, если его можно привести, иначе возвращает ноль. |
| [is](./is/)() const | Определяет, является ли тип упакованного значения, представленного текущим объектом, **V**. |
| [IsBoxedEnum](./isboxedenum/)() override | Определяет, представляет ли текущий объект упакованное значение перечислимого типа. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&, bool) | Упаковывает значение константы перечисления указанного перечисления с указанным именем. Параметр указывает, следует ли игнорировать регистр при интерпретации строки, задающей имя константы перечисления. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&) | Упаковывает значение константы перечисления указанного перечисления с указанным именем. |
| [ToString](./tostring/)() const override | Преобразует упакованное значение, представляемое текущим объектом, в строку. |
| [ToString](../boxedvaluebase/tostring/)(const System::String\&) const | Преобразует упакованный объект в строку, используя указанный форматный шаблон. |
| [unbox](./unbox/)() const | Разупаковывает значение, представляемое текущим объектом. |

## См. также

* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
