---
title: "System::Reflection::MemberInfo class"
linktitle: "MemberInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Reflection::MemberInfo class. Предоставляет информацию отражения о членах. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.reflection/memberinfo/
---
## MemberInfo class


Предоставляет информацию отражения о членах. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MemberInfo : public System::Object
```

## Nested classes

* Class [TypeInternal](./typeinternal/)
## Методы

| Метод | Описание |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Добавляет атрибут в коллекцию. |
| [get_DeclaringType](./get_declaringtype/)() const | Получает объявляющий тип. |
| [get_FullName](./get_fullname/)() const | Получает полное имя члена. Может отличаться в вручную реализованных частях. |
| virtual [get_MemberType](./get_membertype/)() const | Получает значение [System::Reflection::MemberTypes](../membertypes/), указывающее тип члена — метод, конструктор, событие и т.д. |
| [get_Name](./get_name/)() const | Получает имя члена. |
| [get_ReflectedType](./get_reflectedtype/)() const | Получает тип отражённого типа. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом. |
| [GetCustomAttributes](./getcustomattributes/)(bool) const | Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ObjectPtr](./objectptr/) | Псевдоним для умного указателя на [Object](../../system/object/). |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
