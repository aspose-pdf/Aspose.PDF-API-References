---
title: System::Globalization::SortKey class
linktitle: SortKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::SortKey class. Mapping of a string to its sort key. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2200
url: /cpp/system.globalization/sortkey/
---
## SortKey class


Mapping of a string to its sort key. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SortKey : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Compare](./compare/)(const SortKeyPtr\&, const SortKeyPtr\&) | Compares two sort keys. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Checks if the specified object is equal to the current [SortKey](./) object. |
| virtual [get_KeyData](./get_keydata/)() | Gets byte array representing current object. |
| virtual [get_OriginalString](./get_originalstring/)() | Gets original string used to create this object. |
| [GetHashCode](./gethashcode/)() const override | Gets hash code for the current [SortKey](./) object. |
| [operator=](./operator=/)(const SortKey\&) |  |
| [SortKey](./sortkey/)(const SortKey\&) |  |
| [ToString](./tostring/)() const override | Converts current object to its string representation. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
