---
title: System::Reflection::Assembly class
linktitle: Assembly
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::Assembly class. Reflection class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.reflection/assembly/
---
## Assembly class


[Reflection](../) class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Assembly : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Assembly](./assembly/)() | Constructor. |
| virtual [get_CodeBase](./get_codebase/)() const | Gets directory of current assembly. Support is limited. |
| virtual [get_FullName](./get_fullname/)() const | Gets assembly full name. |
| virtual [get_Location](./get_location/)() const | Gets assembly location. Not implemented. |
| static [GetAssembly](./getassembly/)(const TypeInfo\&) | Gets assembly defining specific type. |
| static [GetCallingAssembly](./getcallingassembly/)() | Gets calling assembly. |
| static [GetEntryAssembly](./getentryassembly/)() | Gets entry assembly. |
| static [GetExecutingAssembly](./getexecutingassembly/)() | Gets executing assembly. |
| virtual [GetManifestResourceNames](./getmanifestresourcenames/)() const | Gets names of manifest resources. |
| virtual [GetManifestResourceStream](./getmanifestresourcestream/)(String) const | Gets stream connected to manifest resource. |
| virtual [GetName](./getname/)() const | Gets assembly name. |
| virtual [GetTypes](./gettypes/)() const | Gets types declared by assembly. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
