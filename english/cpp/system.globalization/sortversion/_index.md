---
title: System::Globalization::SortVersion class
linktitle: SortVersion
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::SortVersion class. Provides information about Unicode version used to compare and order strings. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2300
url: /cpp/system.globalization/sortversion/
---
## SortVersion class


Provides information about Unicode version used to compare and order strings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SortVersion : public System::IEquatable<SharedPtr<SortVersion>>
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<SortVersion\>) override | Checks if current [SortVersion](./) instance is equal to a specified [SortVersion](./) object. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Checks if current [SortVersion](./) instance is equal to a specified [SortVersion](./) object. |
| [get_FullVersion](./get_fullversion/)() | Gets full version number. |
| [get_SortId](./get_sortid/)() | Gets unique identifier for this object. |
| [GetHashCode](./gethashcode/)() const override | Gets hash code for the current object. |
| [operator!=](./operator!=/)(const SortVersion\&) | Checks if current [SortVersion](./) instance is not equal to a specified [SortVersion](./) object. |
| [operator=](./operator=/)(const SortVersion\&) |  |
| [operator==](./operator==/)(const SortVersion\&) | Checks if current [SortVersion](./) instance is equal to a specified [SortVersion](./) object. |
| [SortVersion](./sortversion/)(int, const Guid\&) | RTTI information. |
| [SortVersion](./sortversion/)(const SortVersion\&) |  |
## See Also

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
