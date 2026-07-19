---
title: "Класс System::Xml::XmlConvert"
linktitle: "XmlConvert"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlConvert. Кодирует и декодирует имена XML, а также предоставляет методы для преобразования между типами времени выполнения и типами языка определения схем XML (XSD). При преобразовании типов данных возвращаемые значения не зависят от локали в C++."
type: docs
weight: 1200
url: /ru/cpp/system.xml/xmlconvert/
---
## XmlConvert class


Кодирует и декодирует имена XML, а также предоставляет методы для преобразования между типами времени выполнения и типами языка определения [Schema](../../system.xml.schema/) XML (XSD). При преобразовании типов данных возвращаемые значения не зависят от локали.

```cpp
class XmlConvert : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [DecodeName](./decodename/)(const String\&) | Декодирует имя. Этот метод выполняет обратную операцию к методам XmlConvert::EncodeName(String) и XmlConvert::EncodeLocalName(String). |
| static [EncodeLocalName](./encodelocalname/)(const String\&) | Преобразует имя в корректное локальное имя XML. |
| static [EncodeName](./encodename/)(const String\&) | Преобразует имя в корректное имя XML. |
| static [EncodeNmToken](./encodenmtoken/)(const String\&) | Проверяет, что имя соответствует спецификации XML. |
| static [IsNCNameChar](./isncnamechar/)(char16_t) | Проверяет, является ли переданный символ допустимым типом символа без двоеточия. |
| static [IsPublicIdChar](./ispublicidchar/)(char16_t) | Возвращает переданный экземпляр символа, если символ в аргументе является допустимым символом публичного идентификатора, иначе **nullptr**. |
| static [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Проверяет, является ли переданный символ допустимым типом символа начала имени. |
| static [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Проверяет, является ли переданный символ допустимым пробельным символом XML. |
| static [IsXmlChar](./isxmlchar/)(char16_t) | Проверяет, является ли переданный символ допустимым символом XML. |
| static [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Проверяет, является ли переданная пара суррогатных символов допустимым символом XML. |
| static [ToBoolean](./toboolean/)(String) | Преобразует [String](../../system/string/) в эквивалент [Boolean](../../system/boolean/). |
| static [ToByte](./tobyte/)(const String\&) | Преобразует [String](../../system/string/) в эквивалент [Byte](../../system/byte/). |
| static [ToChar](./tochar/)(const String\&) | Преобразует [String](../../system/string/) в эквивалент [Char](../../system/char/). |
| static [ToDateTime](./todatetime/)(const String\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, const String\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, const ArrayPtr\<String\>\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [ToDateTime](./todatetime/)(const String\&, XmlDateTimeSerializationMode) | Преобразует [String](../../system/string/) в [DateTime](../../system/datetime/) с использованием указанного [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const String\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDateTimeOffset](./todatetimeoffset/)(const String\&, const ArrayPtr\<String\>\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [ToDecimal](./todecimal/)(const String\&) | Преобразует [String](../../system/string/) в эквивалент [Decimal](../../system/decimal/). |
| static [ToDouble](./todouble/)(String) | Преобразует [String](../../system/string/) в эквивалент [Double](../../system/double/). |
| static [ToGuid](./toguid/)(const String\&) | Преобразует [String](../../system/string/) в эквивалент [Guid](../../system/guid/). |
| static [ToInt16](./toint16/)(const String\&) | Преобразует [String](../../system/string/) в [Int16](../../system/int16/) эквивалент. |
| static [ToInt32](./toint32/)(const String\&) | Преобразует [String](../../system/string/) в [Int32](../../system/int32/) эквивалент. |
| static [ToInt64](./toint64/)(const String\&) | Преобразует [String](../../system/string/) в [Int64](../../system/int64/) эквивалент. |
| static [ToSByte](./tosbyte/)(const String\&) | Преобразует [String](../../system/string/) в [SByte](../../system/sbyte/) эквивалент. |
| static [ToSingle](./tosingle/)(String) | Преобразует [String](../../system/string/) в [Single](../../system/single/) эквивалент. |
| static [ToString](./tostring/)(bool) | Преобразует [Boolean](../../system/boolean/) в [String](../../system/string/). |
| static [ToString](./tostring/)(char16_t) | Преобразует [Char](../../system/char/) в [String](../../system/string/). |
| static [ToString](./tostring/)(Decimal) | Преобразует [Decimal](../../system/decimal/) в [String](../../system/string/). |
| static [ToString](./tostring/)(int8_t) | Преобразует [SByte](../../system/sbyte/) в [String](../../system/string/). |
| static [ToString](./tostring/)(int16_t) | Преобразует [Int16](../../system/int16/) в [String](../../system/string/). |
| static [ToString](./tostring/)(int32_t) | Преобразует [Int32](../../system/int32/) в [String](../../system/string/). |
| static [ToString](./tostring/)(int64_t) | Преобразует [Int64](../../system/int64/) в [String](../../system/string/). |
| static [ToString](./tostring/)(uint8_t) | Преобразует [Byte](../../system/byte/) в [String](../../system/string/). |
| static [ToString](./tostring/)(uint16_t) | Преобразует [UInt16](../../system/uint16/) в [String](../../system/string/). |
| static [ToString](./tostring/)(uint32_t) | Преобразует [UInt32](../../system/uint32/) в [String](../../system/string/). |
| static [ToString](./tostring/)(uint64_t) | Преобразует [UInt64](../../system/uint64/) в [String](../../system/string/). |
| static [ToString](./tostring/)(float) | Преобразует [Single](../../system/single/) в [String](../../system/string/). |
| static [ToString](./tostring/)(double) | Преобразует [Double](../../system/double/) в [String](../../system/string/). |
| static [ToString](./tostring/)(TimeSpan) | Преобразует [TimeSpan](../../system/timespan/) в [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, const String\&) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/). |
| static [ToString](./tostring/)(DateTime, XmlDateTimeSerializationMode) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/) используя указанный [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/). |
| static [ToString](./tostring/)(DateTimeOffset) | Преобразует предоставленный [DateTimeOffset](../../system/datetimeoffset/) в [String](../../system/string/). |
| static [ToString](./tostring/)(DateTimeOffset, const String\&) | Преобразует предоставленный [DateTimeOffset](../../system/datetimeoffset/) в [String](../../system/string/) в указанном формате. |
| static [ToString](./tostring/)(Guid) | Преобразует [Guid](../../system/guid/) в [String](../../system/string/). |
| static [ToTimeSpan](./totimespan/)(const String\&) | Преобразует [String](../../system/string/) в [TimeSpan](../../system/timespan/) эквивалент. |
| static [ToUInt16](./touint16/)(const String\&) | Преобразует [String](../../system/string/) в эквивалентный [UInt16](../../system/uint16/). |
| static [ToUInt32](./touint32/)(const String\&) | Преобразует [String](../../system/string/) в эквивалентный [UInt32](../../system/uint32/). |
| static [ToUInt64](./touint64/)(const String\&) | Преобразует [String](../../system/string/) в эквивалентный [UInt64](../../system/uint64/). |
| static [VerifyName](./verifyname/)(const String\&) | Проверяет, что имя является допустимым именем в соответствии с рекомендацией W3C Extended Markup Language. |
| static [VerifyNCName](./verifyncname/)(const String\&) | Проверяет, что имя является допустимым **NCName** в соответствии с рекомендацией W3C Extended Markup Language. **NCName** — это имя, которое не может содержать двоеточие. |
| static [VerifyNMTOKEN](./verifynmtoken/)(const String\&) | Проверяет, что строка является допустимым NMTOKEN в соответствии с рекомендацией W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [VerifyPublicId](./verifypublicid/)(const String\&) | Возвращает переданный экземпляр строки, если все символы в аргументе строки являются допустимыми символами публичного идентификатора. |
| static [VerifyTOKEN](./verifytoken/)(const String\&) | Проверяет, что строка является допустимым токеном в соответствии с рекомендацией W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [VerifyWhitespace](./verifywhitespace/)(const String\&) | Возвращает переданный экземпляр строки, если все символы в аргументе строки являются допустимыми символами пробела. |
| static [VerifyXmlChars](./verifyxmlchars/)(const String\&) | Возвращает переданную строку, если все символы и символы суррогатных пар в аргументе строки являются допустимыми XML‑символами; в противном случае выбрасывается [XmlException](../xmlexception/) с информацией о первом обнаруженном недопустимом символе. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
