---
title: "System::Runtime::Serialization::SerializationInfo класс"
linktitle: "SerializationInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::SerializationInfo класс. Содержит набор именованных полей, представляющих сериализованный объект. Не реализовано. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.runtime.serialization/serializationinfo/
---
## SerializationInfo class


Содержит набор именованных полей, представляющих сериализованный объект. Не реализовано. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) функции. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SerializationInfo : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddValue](./addvalue/)(const System::String\&, float) | Записывает значение float. Не реализовано. |
| [AddValue](./addvalue/)(const System::String\&, short) | Записывает значение short. Не реализовано. |
| [AddValue](./addvalue/)(const System::String\&, bool) | Записывает значение boolean. Не реализовано. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Записывает значение объекта. Не реализовано. |
| [AddValue](./addvalue/)(const System::String\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Записывает значение объекта с указанным типом. Не реализовано. |
| [GetValue](./getvalue/)(const System::String\&, const System::TypeInfo\&) | Получает значение из хранилища [SerializationInfo](./). Не реализовано. |
| [SerializationInfo](./serializationinfo/)(const System::TypeInfo\&, const System::SharedPtr\<IFormatterConverter\>\&) | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
