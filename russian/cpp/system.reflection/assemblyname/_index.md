---
title: "System::Reflection::AssemblyName класс"
linktitle: "AssemblyName"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Reflection::AssemblyName класс. Определяет имя сборки. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.reflection/assemblyname/
---
## AssemblyName class


Определяет имя сборки. Объекты этого класса должны выделяться только используя функцию [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AssemblyName : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AssemblyName](./assemblyname/)() | Конструктор. |
| [AssemblyName](./assemblyname/)(const String\&) | Конструктор. |
| [AssemblyName](./assemblyname/)(const String\&, const Version\&) | Конструктор. |
| [get_Name](./get_name/)() | Получает имя сборки. |
| [get_Version](./get_version/)() | Получает версию сборки. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя сборки. |
| [set_Version](./set_version/)(const Version\&) | Устанавливает версию сборки. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
