---
title: "Класс System::ComponentModel::TypeConverter"
linktitle: "TypeConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ComponentModel::TypeConverter класс. Класс, который обрабатывает преобразование типов в модели компонентов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1400
url: /ru/cpp/system.componentmodel/typeconverter/
---
## TypeConverter class


Класс, который обрабатывает преобразование типов в модели компонентов. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TypeConverter : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<System::Object\>\&) | Преобразует объекты. |
| virtual [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Преобразует объекты. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Преобразует строку в объект. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::String\&) | Преобразует инвариантную строку в объект. |
| [ConvertFromInvariantString](./convertfrominvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Преобразует инвариантную строку в объект. |
| [ConvertFromString](./convertfromstring/)(const System::String\&) | Преобразует строку в объект. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) | Преобразует строку в объект. |
| [ConvertFromString](./convertfromstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Преобразует строку в объект. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Преобразует объект в конкретный тип. |
| virtual [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Преобразует объект в конкретный тип. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<System::Object\>\&) | Преобразует объект в инвариантную строку. |
| [ConvertToInvariantString](./converttoinvariantstring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Преобразует объект в инвариантную строку. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<System::Object\>\&) | Преобразует объект в строку. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) | Преобразует объект в строку. |
| [ConvertToString](./converttostring/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Преобразует объект в строку. |
| [TypeConverter](./typeconverter/)() | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
