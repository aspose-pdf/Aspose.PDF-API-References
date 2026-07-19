---
title: "System::Resources::ResourceManager класс"
linktitle: "ResourceManager"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Resources::ResourceManager класс. Предоставляет API для управления ресурсами. Не реализовано. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.resources/resourcemanager/
---
## ResourceManager class


Предоставляет API для управления ресурсами. Не реализовано. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи в функции в качестве аргумента.

```cpp
class ResourceManager : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Получает объект из ресурса. Имя не GetObject(), чтобы обойти проблему с определением GetObjectA. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Получает объект из ресурса. Имя не GetObject(), чтобы обойти проблему с определением GetObjectA. |
| virtual [GetString](./getstring/)(String) | Получает строковый ресурс. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Получает строковый ресурс. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.PDF for C++](../../)
