---
title: "System::Drawing::ImageConverter класс"
linktitle: "ImageConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::ImageConverter класс. Преобразует объекты Image из одного типа данных в другой. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system.drawing/imageconverter/
---
## ImageConverter class


Преобразует объекты [Image](../image/) из одного типа данных в другой. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Методы

| Метод | Описание |
| --- | --- |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Преобразует объект в конкретный тип. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Преобразует объект в конкретный тип. |
| [ImageConverter](./imageconverter/)() | Создаёт новый экземпляр [ImageConverter](./). |
## См. также

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
