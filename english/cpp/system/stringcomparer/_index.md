---
title: System::StringComparer class
linktitle: StringComparer
second_title: Aspose.PDF for C++ API Reference
description: 'System::StringComparer class. Compares strings using different comparison modes. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 5900
url: /cpp/system/stringcomparer/
---
## StringComparer class


Compares strings using different comparison modes. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Methods

| Method | Description |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Compares two strings using current settings. |
| static [Create](./create/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) | Creates culture-specific comparer. |
| [Equals](./equals/)(String, String) const override | Checks if two strings are equal using current settings. |
| static [get_CurrentCulture](./get_currentculture/)() | Current culture comparer singleton. |
| static [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Current culture case-ignoring comparer singleton. |
| static [get_InvariantCulture](./get_invariantculture/)() | Invariant culture comparer singleton. |
| static [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Invariant culture case-ignoring comparer singleton. |
| static [get_Ordinal](./get_ordinal/)() | Ordinal comparer singleton. |
| static [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Ordinal case-ignoring comparer singleton. |
| [GetHashCode](./gethashcode/)(String) const override | Gets string's hash code. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [args_type](./args_type/) | RTTI information. |
## See Also

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
