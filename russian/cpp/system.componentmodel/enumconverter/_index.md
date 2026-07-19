---
title: "System::ComponentModel::EnumConverter класс"
linktitle: "EnumConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ComponentModel::EnumConverter класс. Фиктивный класс для кода, использующего EnumConverter, чтобы он компилировался после перевода. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.componentmodel/enumconverter/
---
## EnumConverter class


Фиктивный класс для кода, использующего EnumConverter, чтобы он компилировался после перевода. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Методы

| Метод | Описание |
| --- | --- |
| [CanConvertFrom](./canconvertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Проверяет, могут ли типы быть преобразованы; не реализовано. |
| [CanConvertTo](./canconvertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Проверяет, могут ли типы быть преобразованы; не реализовано. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) override | Выполняет фактическое преобразование типов; не реализовано. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Выполняет фактическое преобразование типов; не реализовано. |
| [EnumConverter](./enumconverter/)(const System::TypeInfo\&) | Информация RTTI. |
| [get_EnumType](./get_enumtype/)() | Получает тип перечисления, с которым работает [EnumConverter](./); не реализовано. |
## См. также

* Class [TypeConverter](../typeconverter/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
