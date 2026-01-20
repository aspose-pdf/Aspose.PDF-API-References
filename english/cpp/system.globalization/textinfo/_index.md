---
title: System::Globalization::TextInfo class
linktitle: TextInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::TextInfo class. Defines locale-specific text properties. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2800
url: /cpp/system.globalization/textinfo/
---
## TextInfo class


Defines locale-specific text properties. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextInfo : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | RTTI information. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_ANSICodePage](./get_ansicodepage/)() const | Gets ANSI codepage. |
| [get_CultureName](./get_culturename/)() const | Gets cluture name. |
| virtual [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | Gets EBCDIC codepage. |
| [get_IsReadOnly](./get_isreadonly/)() const | Checks if format is read-only. |
| [get_IsRightToLeft](./get_isrighttoleft/)() const | Checks if text is written left to right. |
| [get_LCID](./get_lcid/)() const | Gets locale ID. |
| virtual [get_ListSeparator](./get_listseparator/)() const | Gets list separator. |
| virtual [get_MacCodePage](./get_maccodepage/)() const | Gets Macintosh codepage. |
| virtual [get_OEMCodePage](./get_oemcodepage/)() const | Gets OEM codepage. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [operator=](./operator=/)(const TextInfo\&) |  |
| static [ReadOnly](./readonly/)(const TextInfoPtr\&) | Gets a read only version of culture. |
| virtual [set_ListSeparator](./set_listseparator/)(String) | Sets list separator. |
| [TextInfo](./textinfo/)(const TextInfo\&) | RTTI information. |
| virtual [ToLower](./tolower/)(char_t) const | Converts character to lower case. |
| virtual [ToLower](./tolower/)(String) const | Converts string to lower case. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [ToTitleCase](./totitlecase/)(String) const | Converts string to title case (except for acronyms that are in upper case already). |
| virtual [ToUpper](./toupper/)(char_t) const | Converts character to upper case. |
| virtual [ToUpper](./toupper/)(String) const | Converts string to upper case. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
