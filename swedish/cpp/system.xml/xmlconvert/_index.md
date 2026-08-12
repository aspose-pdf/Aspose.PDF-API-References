---
title: "System::Xml::XmlConvert-klass"
linktitle: "XmlConvert"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlConvert-klass. Kodar och avkodar XML-namn, och tillhandahåller metoder för att konvertera mellan körtidstyper och XML Schema definition language (XSD)-typer. Vid konvertering av datatyper är de returnerade värdena oberoende av lokala inställningar i C++."
type: docs
weight: 1200
url: /sv/cpp/system.xml/xmlconvert/
---
## XmlConvert class


Kodar och avkodar XML-namn, och tillhandahåller metoder för att konvertera mellan körtidstyper och XML [Schema](../../system.xml.schema/) definition language (XSD)-typer. Vid konvertering av datatyper är de returnerade värdena oberoende av lokala inställningar.

```cpp
class XmlConvert : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [DecodeName](./decodename/)(const String\&) | Avkodar ett namn. Denna metod gör motsatsen till metoderna XmlConvert::EncodeName(String) och XmlConvert::EncodeLocalName(String). |
| static [EncodeLocalName](./encodelocalname/)(const String\&) | Konverterar namnet till ett giltigt XML-lokalt namn. |
| static [EncodeName](./encodename/)(const String\&) | Konverterar namnet till ett giltigt XML-namn. |
| static [EncodeNmToken](./encodenmtoken/)(const String\&) | Verifierar att namnet är giltigt enligt XML-specifikationen. |
| static [IsNCNameChar](./isncnamechar/)(char16_t) | Kontrollerar om det angivna tecknet är av en giltig icke‑kolon‑typ. |
| static [IsPublicIdChar](./ispublicidchar/)(char16_t) | Returnerar den överförda teckeninstansen om tecknet i argumentet är ett giltigt public‑id‑tecken, annars **nullptr**. |
| static [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Kontrollerar om det angivna tecknet är av en giltig Start‑namn‑tecken‑typ. |
| static [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Kontrollerar om det angivna tecknet är ett giltigt XML‑blankstegstecken. |
| static [IsXmlChar](./isxmlchar/)(char16_t) | Kontrollerar om det angivna tecknet är ett giltigt XML‑tecken. |
| static [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Kontrollerar om det angivna surrogatparet av tecken är ett giltigt XML‑tecken. |
| static [ToBoolean](./toboolean/)(String) | Konverterar [String](../../system/string/) till en [Boolean](../../system/boolean/)-ekvivalent. |
| static [ToByte](./tobyte/)(const String\&) | Konverterar [String](../../system/string/) till en [Byte](../../system/byte/)-ekvivalent. |
| static [ToChar](./tochar/)(const String\&) | Konverterar [String](../../system/string/) till en [Char](../../system/char/)-ekvivalent. |
| static [ToDateTime](./todatetime/)(const String\&) | Konverterar [String](../../system/string/) till en [DateTime](../../system/datetime/)-ekvivalent. |
| static [ToDateTime](./todatetime/)(const String\&, const String\&) | Konverterar [String](../../system/string/) till en [DateTime](../../system/datetime/)-ekvivalent. |
| static [ToDateTime](./todatetime/)(const String\&, const ArrayPtr\<String\>\&) | Konverterar [String](../../system/string/) till en [DateTime](../../system/datetime/)-ekvivalent. |
| static [ToDateTime](./todatetime/)(const String\&, XmlDateTimeSerializationMode) | Konverterar [String](../../system/string/) till en [DateTime](../../system/datetime/) med den angivna [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&) | Konverterar den angivna [String](../../system/string/) till en [DateTimeOffset](../../system/datetimeoffset/)-ekvivalent. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const String\&) | Konverterar den angivna [String](../../system/string/) till en [DateTimeOffset](../../system/datetimeoffset/)-ekvivalent. |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const ArrayPtr\<String\>\&) | Konverterar den angivna [String](../../system/string/) till en [DateTimeOffset](../../system/datetimeoffset/)-ekvivalent. |
| static [ToDecimal](./todecimal/)(const String\&) | Konverterar [String](../../system/string/) till en [Decimal](../../system/decimal/)-ekvivalent. |
| static [ToDouble](./todouble/)(String) | Konverterar [String](../../system/string/) till en [Double](../../system/double/)-ekvivalent. |
| static [ToGuid](./toguid/)(const String\&) | Konverterar [String](../../system/string/) till en [Guid](../../system/guid/)-ekvivalent. |
| static [ToInt16](./toint16/)(const String\&) | Konverterar [String](../../system/string/) till en [Int16](../../system/int16/) ekvivalent. |
| static [ToInt32](./toint32/)(const String\&) | Konverterar [String](../../system/string/) till en [Int32](../../system/int32/) ekvivalent. |
| static [ToInt64](./toint64/)(const String\&) | Konverterar [String](../../system/string/) till en [Int64](../../system/int64/) ekvivalent. |
| static [ToSByte](./tosbyte/)(const String\&) | Konverterar [String](../../system/string/) till en [SByte](../../system/sbyte/) ekvivalent. |
| static [ToSingle](./tosingle/)(String) | Konverterar [String](../../system/string/) till en [Single](../../system/single/) ekvivalent. |
| static [ToString](./tostring/)(bool) | Konverterar [Boolean](../../system/boolean/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(char16_t) | Konverterar [Char](../../system/char/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(Decimal) | Konverterar [Decimal](../../system/decimal/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(int8_t) | Konverterar [SByte](../../system/sbyte/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(int16_t) | Konverterar [Int16](../../system/int16/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(int32_t) | Konverterar [Int32](../../system/int32/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(int64_t) | Konverterar [Int64](../../system/int64/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(uint8_t) | Konverterar [Byte](../../system/byte/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(uint16_t) | Konverterar [UInt16](../../system/uint16/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(uint32_t) | Konverterar [UInt32](../../system/uint32/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(uint64_t) | Konverterar [UInt64](../../system/uint64/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(float) | Konverterar [Single](../../system/single/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(double) | Konverterar [Double](../../system/double/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(TimeSpan) | Konverterar [TimeSpan](../../system/timespan/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, const String\&) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, XmlDateTimeSerializationMode) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/) med den specificerade [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/). |
| static [ToString](./tostring/)(DateTimeOffset) | Konverterar den angivna [DateTimeOffset](../../system/datetimeoffset/) till en [String](../../system/string/). |
| static [ToString](./tostring/)(DateTimeOffset, const String\&) | Konverterar den angivna [DateTimeOffset](../../system/datetimeoffset/) till en [String](../../system/string/) i det specificerade formatet. |
| static [ToString](./tostring/)(Guid) | Konverterar [Guid](../../system/guid/) till en [String](../../system/string/). |
| static [ToTimeSpan](./totimespan/)(const String\&) | Konverterar [String](../../system/string/) till en [TimeSpan](../../system/timespan/) ekvivalent. |
| static [ToUInt16](./touint16/)(const String\&) | Konverterar [String](../../system/string/) till en [UInt16](../../system/uint16/) motsvarighet. |
| static [ToUInt32](./touint32/)(const String\&) | Konverterar [String](../../system/string/) till en [UInt32](../../system/uint32/) motsvarighet. |
| static [ToUInt64](./touint64/)(const String\&) | Konverterar [String](../../system/string/) till en [UInt64](../../system/uint64/) motsvarighet. |
| static [VerifyName](./verifyname/)(const String\&) | Verifierar att namnet är ett giltigt namn enligt W3C:s rekommendation för Extended Markup Language. |
| static [VerifyNCName](./verifyncname/)(const String\&) | Verifierar att namnet är ett giltigt **NCName** enligt W3C:s rekommendation för Extended Markup Language. Ett **NCName** är ett namn som inte får innehålla ett kolon. |
| static [VerifyNMTOKEN](./verifynmtoken/)(const String\&) | Verifierar att strängen är en giltig NMTOKEN enligt W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-rekommendationen. |
| static [VerifyPublicId](./verifypublicid/)(const String\&) | Returnerar den överförda stränginstansen om alla tecken i strängargumentet är giltiga public id-tecken. |
| static [VerifyTOKEN](./verifytoken/)(const String\&) | Verifierar att strängen är ett giltigt token enligt W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-rekommendationen. |
| static [VerifyWhitespace](./verifywhitespace/)(const String\&) | Returnerar den överförda stränginstansen om alla tecken i strängargumentet är giltiga blankstegstecken. |
| static [VerifyXmlChars](./verifyxmlchars/)(const String\&) | Returnerar den överförda strängen om alla tecken och surrogatpar-tecken i strängargumentet är giltiga XML-tecken, annars kastas ett [XmlException](../xmlexception/) med information om det första ogiltiga tecknet som påträffas. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
