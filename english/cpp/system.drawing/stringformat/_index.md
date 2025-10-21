---
title: System::Drawing::StringFormat class
linktitle: StringFormat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::StringFormat class. Encapsulates text layout information, display manipulations and OpenType features. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.drawing/stringformat/
---
## StringFormat class


Encapsulates text layout information, display manipulations and OpenType features. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringFormat : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Returns an exact copy of the current object. |
| [get_Alignment](./get_alignment/)() const | Returns a value that indicates horizontal alignment of the string. |
| [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Returns a value that indicats the language that is used when local digits are substituted with western digits. |
| [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Returns digit substitution method. |
| [get_FormatFlags](./get_formatflags/)() const | Returns a bitwise combination of [StringFormatFlags](../stringformatflags/) that specifies the string format represented by the current object. |
| static [get_GenericDefault](./get_genericdefault/)() | Returns a [StringFormat](./) object that represents a generic default format. |
| static [get_GenericTypographic](./get_generictypographic/)() | Returns a [StringFormat](./) object that represents a generic typographic format. |
| [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Returns the value that indicates how the hot key prefix is displayed. |
| [get_LineAlignment](./get_linealignment/)() const | Returns a value that indicates vertical alignment of the string. |
| [get_Trimming](./get_trimming/)() const | Returns a value that indicates how the string is trimmed. |
| [GetCharacterRangesCount](./getcharacterrangescount/)() const | Gets a size of the [CharacterRange](../characterrange/) array. |
| [GetTabStops](./gettabstops/)(float\&) const | Returns the tab stops for the current [StringFormat](./) object. |
| [set_Alignment](./set_alignment/)(StringAlignment) | Sets horizontal alignment of the string. |
| [set_FormatFlags](./set_formatflags/)(StringFormatFlags) | Sets the string format flags. |
| [set_HotkeyPrefix](./set_hotkeyprefix/)(Text::HotkeyPrefix) | Sets the value that specifies how the hot key prefix should be displayed. |
| [set_LineAlignment](./set_linealignment/)(StringAlignment) | Sets vertical alignment of the string. |
| [set_Trimming](./set_trimming/)(StringTrimming) | Sets a value that specifies how the string is trimmed. |
| [SetDigitSubstitution](./setdigitsubstitution/)(int32_t, StringDigitSubstitute) | Sets digit substitution language and method. |
| [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const ArrayPtr\<CharacterRange\>\&) | Sets an array of [CharacterRange](../characterrange/) objects that represent the chracter ranges measured by a call to the MeasureCharacterRanges() method. |
| [SetTabStops](./settabstops/)(float, const ArrayPtr\<float\>\&) | Sets the tab stops for the current [StringFormat](./) object. |
| [StringFormat](./stringformat/)() | Constructs a new instance of [StringFormat](./) class. |
| [StringFormat](./stringformat/)(StringFormatFlags, int32_t) | Constructs a new instance of [StringFormat](./) class with the specified format flags and language. |
| [StringFormat](./stringformat/)(const SharedPtr\<StringFormat\>\&) | Copy constructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
