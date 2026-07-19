---
title: "Пространство имён System::Reflection"
linktitle: "System::Reflection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать пространство имён System::Reflection в C++."
type: docs
weight: 5600
url: /ru/cpp/system.reflection/
---



## Классы

| Класс | Описание |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) класс, описывающий сборку. Поддержка ограничена, так как правила сильно различаются между C# и C++. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [AssemblyName](./assemblyname/) | Определяет имя сборки. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Одиночка для регистрации типа в исполняющей сборке. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Базовый тип для одиночек, регистрирующих тип в исполняющей сборке. |
| [ConstructorInfo](./constructorinfo/) | Предоставляет доступ к метаданным конструктора. |
| [FieldInfo](./fieldinfo/) | Обнаруживает атрибуты поля и предоставляет доступ к метаданным поля. |
| [MemberInfo](./memberinfo/) | Предоставляет информацию отражения о членах. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [MethodBase](./methodbase/) | Базовая информация о методе. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [MethodInfo](./methodinfo/) | Представляет информацию о методе класса. |
| [PropertyInfo](./propertyinfo/) | Представляет информацию о свойстве. |
## Enums

| Перечисление | Описание |
| --- | --- |
| [BindingFlags](./bindingflags/) | Определяет режимы поиска членов и типов и их привязки. |
| [FieldAttributes](./fieldattributes/) | Отражённые атрибуты поля. |
| [MemberTypes](./membertypes/) | Помечает каждый тип члена. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | [ReflectionTypeLoadException](./reflectiontypeloadexception/) выбрасывается методом Module.GetTypes, если какая‑либо из классов в модуле не удалось загрузить. Никогда не оборачивайте экземпляры класса [ReflectionTypeLoadException](./reflectiontypeloadexception/) в [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | [TargetInvocationException](./targetinvocationexception/) выбрасывается методами, вызываемыми через отражение. Никогда не оборачивайте экземпляры класса [TargetInvocationException](./targetinvocationexception/) в [System::SmartPtr](../system/smartptr/). |
