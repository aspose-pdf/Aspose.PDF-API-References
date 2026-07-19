---
title: "Класс System::Xml::XmlWriter"
linktitle: "XmlWriter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlWriter. Представляет писатель, который обеспечивает быстрый, без кэширования, однонаправленный способ создания потоков или файлов, содержащих XML‑данные в C++."
type: docs
weight: 4400
url: /ru/cpp/system.xml/xmlwriter/
---
## XmlWriter class


Представляет объект записи, который обеспечивает быстрый, некешированный, только прямой способ создания потоков или файлов, содержащих XML‑данные.

```cpp
class XmlWriter : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Close](./close/)() | При переопределении в производном классе закрывает этот поток и базовый поток. |
| static [Create](./create/)(const String\&) | Создаёт новый экземпляр [XmlWriter](./), используя указанный файл. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlWriterSettings\>) | Создаёт новый экземпляр [XmlWriter](./), используя файл и объект [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Создаёт новый экземпляр [XmlWriter](./), используя указанный поток. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) | Создаёт новый экземпляр [XmlWriter](./), используя поток и объект [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&) | Создаёт новый экземпляр [XmlWriter](./), используя указанный TextWriter. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Создаёт новый экземпляр [XmlWriter](./), используя TextWriter и объекты [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&) | Создаёт новый экземпляр [XmlWriter](./), используя указанный [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) | Создаёт новый экземпляр [XmlWriter](./), используя [Text::StringBuilder](../../system.text/stringbuilder/) и объекты [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&) | Создаёт новый экземпляр [XmlWriter](./), используя указанный объект [XmlWriter](./). |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Создаёт новый экземпляр [XmlWriter](./), используя указанный объект [XmlWriter](./) и объекты [XmlWriterSettings](../xmlwritersettings/). |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим экземпляром класса [XmlWriter](./). |
| virtual [Flush](./flush/)() | При переопределении в производном классе сбрасывает всё, что находится в буфере, в базовые потоки и также сбрасывает базовый поток. |
| virtual [get_Settings](./get_settings/)() | Возвращает объект [XmlWriterSettings](../xmlwritersettings/), используемый для создания этого экземпляра [XmlWriter](./). |
| virtual [get_WriteState](./get_writestate/)() | При переопределении в производном классе получает состояние записывающего объекта. |
| virtual [get_XmlLang](./get_xmllang/)() | При переопределении в производном классе возвращает текущую область **xml:lang**. |
| virtual [get_XmlSpace](./get_xmlspace/)() | При переопределении в производном классе получает объект [XmlSpace](../xmlspace/), представляющий текущую область **xml:space**. |
| virtual [LookupPrefix](./lookupprefix/)(String) | При переопределении в производном классе возвращает ближайший префикс, определённый в текущей области пространства имён для URI пространства имён. |
| virtual [WriteAttributes](./writeattributes/)(SharedPtr\<XmlReader\>, bool) | При переопределении в производном классе записывает все атрибуты, найденные в текущей позиции [XmlReader](../xmlreader/). |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем, URI пространства имён и значением. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&) | При переопределении в производном классе записывает атрибут с указанным локальным именем и значением. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&, const String\&) | При переопределении в производном классе записывает атрибут с указанным префиксом, локальным именем, URI пространства имён и значением. |
| virtual [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | При переопределении в производном классе кодирует указанные бинарные байты в Base64 и записывает полученный текст. |
| virtual [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | При переопределении в производном классе кодирует указанные бинарные байты как **BinHex** и записывает полученный текст. |
| virtual [WriteCData](./writecdata/)(String) | При переопределении в производном классе записывает блок **...**, содержащий указанный текст. |
| virtual [WriteCharEntity](./writecharentity/)(char16_t) | При переопределении в производном классе принудительно генерирует символьную сущность для указанного значения Unicode‑символа. |
| virtual [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | При переопределении в производном классе записывает текст буфер за буфером. |
| virtual [WriteComment](./writecomment/)(String) | При переопределении в производном классе записывает комментарий ****, содержащий указанный текст. |
| virtual [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) | При переопределении в производном классе записывает объявление DOCTYPE с указанным именем и необязательными атрибутами. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&) | Записывает элемент с указанным локальным именем и значением. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&) | Записывает элемент с указанным локальным именем, URI пространства имён и значением. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&, const String\&) | Записывает элемент с указанным префиксом, локальным именем, URI пространства имён и значением. |
| virtual [WriteEndAttribute](./writeendattribute/)() | При переопределении в производном классе закрывает предыдущий вызов XmlWriter::WriteStartAttribute(String,String). |
| virtual [WriteEndDocument](./writeenddocument/)() | При переопределении в производном классе закрывает все открытые элементы или атрибуты и возвращает записывающий объект в состояние Start. |
| virtual [WriteEndElement](./writeendelement/)() | При переопределении в производном классе закрывает один элемент и снимает соответствующую область пространства имён. |
| virtual [WriteEntityRef](./writeentityref/)(const String\&) | При переопределении в производном классе записывает ссылку на сущность как **&name**;. |
| virtual [WriteFullEndElement](./writefullendelement/)() | При переопределении в производном классе закрывает один элемент и снимает соответствующую область пространства имён. |
| virtual [WriteName](./writename/)(const String\&) | При переопределении в производном классе записывает указанное имя, гарантируя, что оно является допустимым именем согласно рекомендациям W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNmToken](./writenmtoken/)(const String\&) | При переопределении в производном классе записывает указанное имя, гарантируя, что оно является допустимым NmToken согласно рекомендациям W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNode](./writenode/)(SharedPtr\<XmlReader\>, bool) | При переопределении в производном классе копирует всё из reader в writer и перемещает reader к началу следующего sibling. |
| virtual [WriteNode](./writenode/)(SharedPtr\<XPath::XPathNavigator\>, bool) | Копирует всё из объекта XPathNavigator в writer. Позиция XPathNavigator остаётся неизменной. |
| virtual [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) | При переопределении в производном классе записывает инструкцию обработки с пробелом между именем и текстом следующим образом: **<?name text?>**. |
| virtual [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) | При переопределении в производном классе записывает имя, квалифицированное пространством имён. Этот метод ищет префикс, находящийся в области видимости для указанного пространства имён. |
| virtual [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | При переопределении в производном классе вручную записывает необработанную разметку из буфера символов. |
| virtual [WriteRaw](./writeraw/)(const String\&) | При переопределении в производном классе вручную записывает необработанную разметку из строки. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&) | Записывает начало атрибута с указанным локальным именем и URI пространства имён. |
| virtual [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) | При переопределении в производном классе записывает начало атрибута с указанным префиксом, локальным именем и URI пространства имён. |
| [WriteStartAttribute](./writestartattribute/)(const String\&) | Записывает начало атрибута с указанным локальным именем. |
| virtual [WriteStartDocument](./writestartdocument/)() | При переопределении в производном классе записывает объявление XML с версией "1.0". |
| virtual [WriteStartDocument](./writestartdocument/)(bool) | При переопределении в производном классе записывает объявление XML с версией "1.0" и атрибутом standalone. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&) | При переопределении в производном классе записывает указанный стартовый тег и связывает его с заданным пространством имён. |
| virtual [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) | При переопределении в производном классе записывает указанный стартовый тег и связывает его с заданным пространством имён и префиксом. |
| [WriteStartElement](./writestartelement/)(const String\&) | При переопределении в производном классе записывает стартовый тег с указанным локальным именем. |
| virtual [WriteString](./writestring/)(const String\&) | При переопределении в производном классе записывает переданное текстовое содержимое. |
| virtual [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | При переопределении в производном классе генерирует и записывает сущность суррогатного символа для пары суррогатных символов. |
| virtual [WriteValue](./writevalue/)(SharedPtr\<Object\>) | Записывает значение объекта. |
| virtual [WriteValue](./writevalue/)(const String\&) | Записывает значение [String](../../system/string/). |
| virtual [WriteValue](./writevalue/)(bool) | Записывает значение [Boolean](../../system/boolean/). |
| virtual [WriteValue](./writevalue/)(DateTime) | Записывает значение [DateTime](../../system/datetime/). |
| virtual [WriteValue](./writevalue/)(DateTimeOffset) | Записывает значение [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [WriteValue](./writevalue/)(double) | Записывает значение [Double](../../system/double/). |
| virtual [WriteValue](./writevalue/)(float) | Записывает число с одинарной точностью (single-precision floating-point number). |
| virtual [WriteValue](./writevalue/)(Decimal) | Записывает значение [Decimal](../../system/decimal/). |
| virtual [WriteValue](./writevalue/)(int32_t) | Записывает значение [Int32](../../system/int32/). |
| virtual [WriteValue](./writevalue/)(int64_t) | Записывает значение [Int64](../../system/int64/). |
| virtual [WriteWhitespace](./writewhitespace/)(String) | При переопределении в производном классе записывает указанный пробел. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
