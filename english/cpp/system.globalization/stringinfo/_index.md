---
title: System::Globalization::StringInfo class
linktitle: StringInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::StringInfo class. Splitter to iterate through string parts. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.globalization/stringinfo/
---
## StringInfo class


Splitter to iterate through string parts. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringInfo : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LengthInTextElements](./get_lengthintextelements/)() const | Gets number of text items in [StringInfo](./) object. |
| [get_String](./get_string/)() const | Gets the value of the [StringInfo](./) object. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&) | Gets first element in the specified string. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&, int) | Gets element at the specified index of the specified string. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&) | Creates enumerator to iterate through string's characters. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&, int) | Creates enumerator to iterate through string's characters starting at the specified index. |
| [operator=](./operator=/)(const StringInfo\&) |  |
| static [ParseCombiningCharacters](./parsecombiningcharacters/)(const String\&) | Gets indexes of the base characters, high surrogates and control characters. |
| [set_String](./set_string/)(const String\&) | Sets the value of the [StringInfo](./) object. |
| [StringInfo](./stringinfo/)() | RTTI information. |
| [StringInfo](./stringinfo/)(const String\&) | Constructor. |
| [StringInfo](./stringinfo/)(const StringInfo\&) |  |
| [SubstringByTextElements](./substringbytextelements/)(int) const | Gets substring of text elements from the specified text element through the last text element. |
| [SubstringByTextElements](./substringbytextelements/)(int, int) const | Gets substring of text elements from the specified text element through the specified number of text elements. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
