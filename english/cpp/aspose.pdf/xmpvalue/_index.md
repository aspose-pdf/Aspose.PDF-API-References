---
title: Aspose::Pdf::XmpValue class
linktitle: XmpValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmpValue class. Represents XMP value in C++.'
type: docs
weight: 20800
url: /cpp/aspose.pdf/xmpvalue/
---
## XmpValue class


Represents XMP value.

```cpp
class XmpValue : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsArray](./get_isarray/)() | Returns true is [XmpValue](./) is array. |
| [get_IsDateTime](./get_isdatetime/)() const | Returns true if value is DateTime. |
| [get_IsDouble](./get_isdouble/)() const | Returns true if value is floating point value. |
| [get_IsField](./get_isfield/)() | Returns true if [XmpValue](./) is field. |
| [get_IsInteger](./get_isinteger/)() const | Returns true if value is integer. |
| [get_IsNamedValue](./get_isnamedvalue/)() const | Returns true if [XmpValue](./) is named value. |
| [get_IsNamedValues](./get_isnamedvalues/)() | Returns true is [XmpValue](./) represents named values. |
| [get_IsRaw](./get_israw/)() | Value is unsupported/unknown and raw XML code is provided. |
| [get_IsString](./get_isstring/)() | Returns true if value is string. |
| [get_IsStructure](./get_isstructure/)() | Returns true is [XmpValue](./) represents structure. |
| static [to_KeyValuePair](./to_keyvaluepair/)(System::SharedPtr\<XmpValue\>) | Converts [XmpValue](./) to named value. |
| static [to_KeyValuePairArray](./to_keyvaluepairarray/)(System::SharedPtr\<XmpValue\>) | Converts XmlValue to named collection value. |
| static [to_ObjectArray](./to_objectarray/)(System::SharedPtr\<XmpValue\>) | Converts [XmpValue](./) into array. |
| static [to_String](./to_string/)(System::SharedPtr\<XmpValue\>) | Converts [XmpValue](./) into string. |
| static [to_XmpValue](./to_xmpvalue/)(System::String) | Converts string to [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(int32_t) | Converts integer into [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(double) | Converts double into [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(System::DateTime) | Converts DateTime into [XmpValue](./). |
| static [to_XmpValue](./to_xmpvalue/)(System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Converts array to [XmpValue](./). |
| static [to_XmpValueArray](./to_xmpvaluearray/)(System::SharedPtr\<XmpValue\>) | Converts [XmpValue](./) to array. |
| [ToArray](./toarray/)() | Returns array. |
| [ToDateTime](./todatetime/)() | Converts to date time. |
| [ToDictionary](./todictionary/)() | Returns dictionary which contains named values. |
| [ToDouble](./todouble/)() | Converts to double. |
| [ToField](./tofield/)() | Returns XMP value as XMP field. |
| [ToInteger](./tointeger/)() | Converts to integer. |
| [ToNamedValue](./tonamedvalue/)() | Returns XMP value as named value. |
| [ToNamedValues](./tonamedvalues/)() | Returns XMP value as named value collection. |
| [ToRaw](./toraw/)() | Raw XML code for unknown/unsupported values. |
| [ToString](./tostring/)(System::SharedPtr\<System::IFormatProvider\>) | Returns string representation. |
| [ToString](./tostring/)() const override | Returns string representation of [XmpValue](./). |
| [ToStringValue](./tostringvalue/)() | Converts to string. |
| [ToStructure](./tostructure/)() | Returns XMP value as structure (set of fields). |
| [XmpValue](./xmpvalue/)(System::String) | Constructor for string value. |
| [XmpValue](./xmpvalue/)(int32_t) | Consructor for integer value. |
| [XmpValue](./xmpvalue/)(double) | Constructor for floating point Value. |
| [XmpValue](./xmpvalue/)(System::DateTime) | Constructor for date time value. |
| [XmpValue](./xmpvalue/)(System::ArrayPtr\<System::SharedPtr\<XmpValue\>\>) | Constructor for array value. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
