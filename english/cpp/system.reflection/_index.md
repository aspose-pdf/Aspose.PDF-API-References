---
title: System::Reflection namespace
linktitle: System::Reflection
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Reflection namespace in C++.'
type: docs
weight: 5600
url: /cpp/system.reflection/
---



## Classes

| Class | Description |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [AssemblyName](./assemblyname/) | Defines assembly name. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton to register type in executing assembly. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Base type for singletons to register type in executing assembly. |
| [ConstructorInfo](./constructorinfo/) | Provides access to constructor metadata. |
| [FieldInfo](./fieldinfo/) | Discovers the attributes of a field and provides access to field metadata. |
| [MemberInfo](./memberinfo/) | Provides reflection information on members. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MethodBase](./methodbase/) | Base information on method. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [MethodInfo](./methodinfo/) | Represents information on class method. |
| [PropertyInfo](./propertyinfo/) | Represents property information. |
## Enums

| Enum | Description |
| --- | --- |
| [BindingFlags](./bindingflags/) | Degines members and types lookup modes and bindings. |
| [FieldAttributes](./fieldattributes/) | Reflected field attributes. |
| [MemberTypes](./membertypes/) | Marks each type of member. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | [ReflectionTypeLoadException](./reflectiontypeloadexception/) is thrown by the Module.GetTypes method if any of the classes in a module fail to load. Never wrap the [ReflectionTypeLoadException](./reflectiontypeloadexception/) class instances into [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | [TargetInvocationException](./targetinvocationexception/) is thrown by methods invoked through reflection. Never wrap the [TargetInvocationException](./targetinvocationexception/) class instances into [System::SmartPtr](../system/smartptr/). |
