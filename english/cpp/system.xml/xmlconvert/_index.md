---
title: System::Xml::XmlConvert class
linktitle: XmlConvert
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlConvert class. Encodes and decodes XML names, and provides methods for converting between runtime types and XML Schema definition language (XSD) types. When converting data types, the values returned are locale-independent in C++.'
type: docs
weight: 1200
url: /cpp/system.xml/xmlconvert/
---
## XmlConvert class


Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [DecodeName](./decodename/)(const String\&) | Decodes a name. This method does the reverse of the XmlConvert::EncodeName(String) and XmlConvert::EncodeLocalName(String) methods. |
| static [EncodeLocalName](./encodelocalname/)(const String\&) | Converts the name to a valid XML local name. |
| static [EncodeName](./encodename/)(const String\&) | Converts the name to a valid XML name. |
| static [EncodeNmToken](./encodenmtoken/)(const String\&) | Verifies the name is valid according to the XML specification. |
| static [IsNCNameChar](./isncnamechar/)(char16_t) | Checks whether the passed-in character is a valid non-colon character type. |
| static [IsPublicIdChar](./ispublicidchar/)(char16_t) | Returns the passed-in character instance if the character in the argument is a valid public id character, otherwise **nullptr**. |
| static [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Checks if the passed-in character is a valid Start Name Character type. |
| static [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Checks if the passed-in character is a valid XML whitespace character. |
| static [IsXmlChar](./isxmlchar/)(char16_t) | Checks if the passed-in character is a valid XML character. |
| static [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Checks if the passed-in surrogate pair of characters is a valid XML character. |
| static [ToBoolean](./toboolean/)(String) | Converts the [String](../../system/string/) to a [Boolean](../../system/boolean/) equivalent. |
| static [ToByte](./tobyte/)(const String\&) | Converts the [String](../../system/string/) to a [Byte](../../system/byte/) equivalent. |
| static [ToChar](./tochar/)(const String\&) | Converts the [String](../../system/string/) to a [Char](../../system/char/) equivalent. |
| static [ToDateTime](./todatetime/)(const String\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [ToDateTime](./todatetime/)(const String\&, const String\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [ToDateTime](./todatetime/)(const String\&, const ArrayPtr\<String\>\&) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) equivalent. |
| static [ToDateTime](./todatetime/)(const String\&, XmlDateTimeSerializationMode) | Converts the [String](../../system/string/) to a [DateTime](../../system/datetime/) using the [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/) specified. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const String\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const ArrayPtr\<String\>\&) | Converts the supplied [String](../../system/string/) to a [DateTimeOffset](../../system/datetimeoffset/) equivalent. |
| static [ToDecimal](./todecimal/)(const String\&) | Converts the [String](../../system/string/) to a [Decimal](../../system/decimal/) equivalent. |
| static [ToDouble](./todouble/)(String) | Converts the [String](../../system/string/) to a [Double](../../system/double/) equivalent. |
| static [ToGuid](./toguid/)(const String\&) | Converts the [String](../../system/string/) to a [Guid](../../system/guid/) equivalent. |
| static [ToInt16](./toint16/)(const String\&) | Converts the [String](../../system/string/) to a [Int16](../../system/int16/) equivalent. |
| static [ToInt32](./toint32/)(const String\&) | Converts the [String](../../system/string/) to a [Int32](../../system/int32/) equivalent. |
| static [ToInt64](./toint64/)(const String\&) | Converts the [String](../../system/string/) to a [Int64](../../system/int64/) equivalent. |
| static [ToSByte](./tosbyte/)(const String\&) | Converts the [String](../../system/string/) to a [SByte](../../system/sbyte/) equivalent. |
| static [ToSingle](./tosingle/)(String) | Converts the [String](../../system/string/) to a [Single](../../system/single/) equivalent. |
| static [ToString](./tostring/)(bool) | Converts the [Boolean](../../system/boolean/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(char16_t) | Converts the [Char](../../system/char/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(Decimal) | Converts the [Decimal](../../system/decimal/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(int8_t) | Converts the [SByte](../../system/sbyte/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(int16_t) | Converts the [Int16](../../system/int16/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(int32_t) | Converts the [Int32](../../system/int32/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(int64_t) | Converts the [Int64](../../system/int64/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(uint8_t) | Converts the [Byte](../../system/byte/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(uint16_t) | Converts the [UInt16](../../system/uint16/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(uint32_t) | Converts the [UInt32](../../system/uint32/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(uint64_t) | Converts the [UInt64](../../system/uint64/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(float) | Converts the [Single](../../system/single/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(double) | Converts the [Double](../../system/double/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(TimeSpan) | Converts the [TimeSpan](../../system/timespan/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, const String\&) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, XmlDateTimeSerializationMode) | Converts the [DateTime](../../system/datetime/) to a [String](../../system/string/) using the [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/) specified. |
| static [ToString](./tostring/)(DateTimeOffset) | Converts the supplied [DateTimeOffset](../../system/datetimeoffset/) to a [String](../../system/string/). |
| static [ToString](./tostring/)(DateTimeOffset, const String\&) | Converts the supplied [DateTimeOffset](../../system/datetimeoffset/) to a [String](../../system/string/) in the specified format. |
| static [ToString](./tostring/)(Guid) | Converts the [Guid](../../system/guid/) to a [String](../../system/string/). |
| static [ToTimeSpan](./totimespan/)(const String\&) | Converts the [String](../../system/string/) to a [TimeSpan](../../system/timespan/) equivalent. |
| static [ToUInt16](./touint16/)(const String\&) | Converts the [String](../../system/string/) to a [UInt16](../../system/uint16/) equivalent. |
| static [ToUInt32](./touint32/)(const String\&) | Converts the [String](../../system/string/) to a [UInt32](../../system/uint32/) equivalent. |
| static [ToUInt64](./touint64/)(const String\&) | Converts the [String](../../system/string/) to a [UInt64](../../system/uint64/) equivalent. |
| static [VerifyName](./verifyname/)(const String\&) | Verifies that the name is a valid name according to the W3C Extended Markup Language recommendation. |
| static [VerifyNCName](./verifyncname/)(const String\&) | Verifies that the name is a valid **NCName** according to the W3C Extended Markup Language recommendation. An **NCName** is a name that cannot contain a colon. |
| static [VerifyNMTOKEN](./verifynmtoken/)(const String\&) | Verifies that the string is a valid NMTOKEN according to the W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes recommendation. |
| static [VerifyPublicId](./verifypublicid/)(const String\&) | Returns the passed in string instance if all the characters in the string argument are valid public id characters. |
| static [VerifyTOKEN](./verifytoken/)(const String\&) | Verifies that the string is a valid token according to the W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes recommendation. |
| static [VerifyWhitespace](./verifywhitespace/)(const String\&) | Returns the passed-in string instance if all the characters in the string argument are valid whitespace characters. |
| static [VerifyXmlChars](./verifyxmlchars/)(const String\&) | Returns the passed-in string if all the characters and surrogate pair characters in the string argument are valid XML characters, otherwise an [XmlException](../xmlexception/) is thrown with information on the first invalid character encountered. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
