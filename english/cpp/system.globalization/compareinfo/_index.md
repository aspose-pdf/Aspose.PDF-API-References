---
title: System::Globalization::CompareInfo class
linktitle: CompareInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::CompareInfo class. Makes culture-sensitive string comparison. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.globalization/compareinfo/
---
## CompareInfo class


Makes culture-sensitive string comparison. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CompareInfo : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Compare](./compare/)(const String\&, const String\&) const | Compares strings. Not implemented. |
| virtual [Compare](./compare/)(const String\&, const String\&, CompareOptions) const | Compares strings. Only Ordinal and OrdinalIgnoreCase modes are supported. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int) const | Compares a section of one string with a section of second string. Not implemented. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int, CompareOptions) const | Compares the end section of one string with the end section of second string using string comparison methods. Not implemented. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int) const | Compares the end section of one string with the end section of second string. Not implemented. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int, CompareOptions) const | Compares a section of one string with a section of second string using string comparison methods. Not implemented. |
| [CompareInfo](./compareinfo/)(const CompareInfo\&) | RTTI information. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LCID](./get_lcid/)() const | Gets LCID of the culture associated with comparer. |
| virtual [get_Name](./get_name/)() const | Gets name of the culture associated with comparer. |
| [get_Version](./get_version/)() const | Gets information about sort version. |
| static [GetCompareInfo](./getcompareinfo/)(int, const SharedPtr\<Reflection::Assembly\>\&) | Gets [CompareInfo](./) associated with the specified culture and using string comparison methods in the specified assembly. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Gets [CompareInfo](./) associated with the specified culture and using string comparison methods in the specified assembly. |
| static [GetCompareInfo](./getcompareinfo/)(int) | Gets [CompareInfo](./) associated with the specified culture. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&) | Gets [CompareInfo](./) associated with the specified culture. |
| virtual [GetHashCode](./gethashcode/)(const String\&, CompareOptions) const | Gets string hash code based on specified comparison options. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [GetSortKey](./getsortkey/)(const String\&, CompareOptions) const | Gets [SortKey](../sortkey/) object for the specified string using specified compare options. |
| virtual [GetSortKey](./getsortkey/)(const String\&) const | Gets [SortKey](../sortkey/) object for the specified string. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int) const | Looks for substring. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, CompareOptions) const | Looks for substring. Only Ordinal mode is supported. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int, CompareOptions) const | Looks for substring. Only Ordinal mode is supported. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int, CompareOptions) const | Looks for the specified character. Only Ordinal mode is supported. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int) const | Looks for substring. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t) const | Looks for the specified character. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&) const | Looks for substring. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, CompareOptions) const | Looks for the specified character. Only Ordinal mode is supported. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int) const | Looks for the specified character. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int) const | Looks for the specified character. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, CompareOptions) const | Looks for substring. Only Ordinal mode is supported. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, CompareOptions) const | Looks for the specified character. Only Ordinal mode is supported. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&, CompareOptions) const | Checks if the specified string starts with the specified prefix using the specified compare options. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&) const | Checks if the specified string starts with the specified prefix. |
| static [IsSortable](./issortable/)(char16_t) | Checks whether a specified character is sortable. |
| static [IsSortable](./issortable/)(const String\&) | Checks whether a specified string is sortable. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&, CompareOptions) const | Checks if the specified string ends with the specified suffix using the specified compare options. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&) const | Checks if the specified string ends with the specified suffix. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&) const | Searches last occurrence of the specified substring. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int, CompareOptions) const | Searches last occurrence of the specified substring using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int, CompareOptions) const | Searches last occurrence of the specified character using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int) const | Searches last occurrence of the specified string. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, CompareOptions) const | Searches last occurrence of the specified string using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, CompareOptions) const | Searches last occurrence of the specified character using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int) const | Searches last occurrence of the specified string. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int) const | Searches last occurrence of the specified character. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, CompareOptions) const | Searches last occurrence of the specified string using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, CompareOptions) const | Searches last occurrence of the specified character using the specified compare options. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t) const | Searches last occurrence of the specified character. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int) const | Searches last occurrence of the specified character. |
| [operator=](./operator=/)(const CompareInfo\&) |  |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
