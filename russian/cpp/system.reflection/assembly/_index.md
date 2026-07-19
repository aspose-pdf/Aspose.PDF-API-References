---
title: "Класс System::Reflection::Assembly"
linktitle: "Assembly"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Reflection::Assembly. Класс рефлексии, описывающий сборку. Поддержка ограничена, так как правила сильно различаются между C# и C++. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.reflection/assembly/
---
## Assembly class


[Reflection](../) class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Assembly : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Assembly](./assembly/)() | Конструктор. |
| virtual [get_CodeBase](./get_codebase/)() const | Получает каталог текущей сборки. Поддержка ограничена. |
| virtual [get_FullName](./get_fullname/)() const | Получает полное имя сборки. |
| virtual [get_Location](./get_location/)() const | Получает расположение сборки. Не реализовано. |
| static [GetAssembly](./getassembly/)(const TypeInfo\&) | Получает сборку, определяющую конкретный тип. |
| static [GetCallingAssembly](./getcallingassembly/)() | Получает вызывающую сборку. |
| static [GetEntryAssembly](./getentryassembly/)() | Получает главную сборку. |
| static [GetExecutingAssembly](./getexecutingassembly/)() | Получает исполняемую сборку. |
| virtual [GetManifestResourceNames](./getmanifestresourcenames/)() const | Получает имена ресурсов манифеста. |
| virtual [GetManifestResourceStream](./getmanifestresourcestream/)(String) const | Получает поток, подключённый к ресурсу манифеста. |
| virtual [GetName](./getname/)() const | Получает имя сборки. |
| virtual [GetTypes](./gettypes/)() const | Получает типы, объявленные в сборке. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
