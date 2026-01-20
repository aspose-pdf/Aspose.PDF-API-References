---
title: System::Globalization::IdnMapping class
linktitle: IdnMapping
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::IdnMapping class. IdnMapping used to map names to Punycode. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.globalization/idnmapping/
---
## IdnMapping class


[IdnMapping](./) used to map names to Punycode. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IdnMapping : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares two [IdnMapping](./) objects. |
| [get_AllowUnassigned](./get_allowunassigned/)() const | Gets flag that indicates if unassigned code points used in operations. |
| [get_UseStd3AsciiRules](./get_usestd3asciirules/)() const | Gets flag that indicates if standard naming conventions used in operations. |
| [GetAscii](./getascii/)(const String\&) const | [Convert](../../system/convert/) unicode domain name to ascii equivalent. |
| [GetAscii](./getascii/)(const String\&, int) const | [Convert](../../system/convert/) unicode domain name to ascii equivalent. |
| [GetAscii](./getascii/)(const String\&, int, int) const | [Convert](../../system/convert/) unicode domain name to ascii equivalent. |
| [GetHashCode](./gethashcode/)() const override | Gets hash code for current [IdnMapping](./) object. |
| [GetUnicode](./getunicode/)(const String\&) const | [Convert](../../system/convert/) ascii domain name to unicode equivalent. |
| [GetUnicode](./getunicode/)(const String\&, int) const | [Convert](../../system/convert/) ascii domain name to unicode equivalent. |
| [GetUnicode](./getunicode/)(const String\&, int, int) const | [Convert](../../system/convert/) ascii domain name to unicode equivalent. |
| [IdnMapping](./idnmapping/)() | RTTI information. |
| [IdnMapping](./idnmapping/)(const IdnMapping\&) |  |
| [operator=](./operator=/)(const IdnMapping\&) |  |
| [set_AllowUnassigned](./set_allowunassigned/)(bool) | Sets flag that indicates if unassigned code points used in operations. |
| [set_UseStd3AsciiRules](./set_usestd3asciirules/)(bool) | Sets flag that indicates if standard naming conventions used in operations. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
