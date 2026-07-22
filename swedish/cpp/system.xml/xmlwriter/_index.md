---
title: "System::Xml::XmlWriter klass"
linktitle: "XmlWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter klass. Representerar en skrivare som tillhandahåller ett snabbt, icke-cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data i C++."
type: docs
weight: 4400
url: /sv/cpp/system.xml/xmlwriter/
---
## XmlWriter class


Representerar en skrivare som tillhandahåller ett snabbt, icke-cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML‑data.

```cpp
class XmlWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | När den åsidosätts i en avledd klass, stänger den här strömmen och den underliggande strömmen. |
| static [Create](./create/)(const String\&) | Skapar en ny [XmlWriter](./)-instans med det angivna filnamnet. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlWriterSettings\>) | Skapar en ny [XmlWriter](./)-instans med filnamnet och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna strömmen. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) | Skapar en ny [XmlWriter](./)-instans med strömmen och [XmlWriterSettings](../xmlwritersettings/)-objektet. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna TextWriter. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Skapar en ny [XmlWriter](./)-instans med TextWriter och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&) | Skapar en ny [XmlWriter](./)-instans med den angivna [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) | Skapar en ny [XmlWriter](./)-instans med [Text::StringBuilder](../../system.text/stringbuilder/) och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&) | Skapar en ny [XmlWriter](./)-instans med det angivna [XmlWriter](./)-objektet. |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Skapar en ny [XmlWriter](./)-instans med det angivna [XmlWriter](./)- och [XmlWriterSettings](../xmlwritersettings/)-objekten. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av den aktuella instansen av [XmlWriter](./)-klassen. |
| virtual [Flush](./flush/)() | När den åsidosätts i en avledd klass tömmer den allt som finns i bufferten till de underliggande strömmarna och tömmer även den underliggande strömmen. |
| virtual [get_Settings](./get_settings/)() | Returnerar objektet [XmlWriterSettings](../xmlwritersettings/) som används för att skapa detta [XmlWriter](./)-instans. |
| virtual [get_WriteState](./get_writestate/)() | När den åsidosätts i en avledd klass hämtar den skrivarens tillstånd. |
| virtual [get_XmlLang](./get_xmllang/)() | När den åsidosätts i en avledd klass, hämtar den aktuella **xml:lang**-omfånget. |
| virtual [get_XmlSpace](./get_xmlspace/)() | När den åsidosätts i en avledd klass hämtar den ett [XmlSpace](../xmlspace/) som representerar det aktuella **xml:space**-omfånget. |
| virtual [LookupPrefix](./lookupprefix/)(String) | När den åsidosätts i en avledd klass returnerar den det närmaste prefixet som definierats i det aktuella namnrymdsomfånget för namnrymdens URI. |
| virtual [WriteAttributes](./writeattributes/)(SharedPtr\<XmlReader\>, bool) | När den åsidosätts i en avledd klass skriver den ut alla attribut som hittas på den aktuella positionen i [XmlReader](../xmlreader/). |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den ett attribut med det angivna lokala namnet, namnrymdens URI och värdet. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den ut attributet med det angivna lokala namnet och värdet. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den ut attributet med det angivna prefixet, lokala namnet, namnrymdens URI och värdet. |
| virtual [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | När den åsidosätts i en avledd klass kodar den de angivna binära bytena som Base64 och skriver ut den resulterande texten. |
| virtual [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | När den åsidosätts i en avledd klass kodar den de angivna binära bytena som **BinHex** och skriver ut den resulterande texten. |
| virtual [WriteCData](./writecdata/)(String) | När den åsidosätts i en avledd klass skriver den ut ett **...**-block som innehåller den angivna texten. |
| virtual [WriteCharEntity](./writecharentity/)(char16_t) | När den åsidosätts i en avledd klass tvingar den genereringen av en teckenentitet för det angivna Unicode-teckenvärdet. |
| virtual [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | När den åsidosätts i en avledd klass skriver den text en buffert i taget. |
| virtual [WriteComment](./writecomment/)(String) | När den åsidosätts i en avledd klass skriver den ut en kommentar **** som innehåller den angivna texten. |
| virtual [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&) | Skriver ett element med det angivna lokala namnet och värdet. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&) | Skriver ett element med det angivna lokala namnet, namnrymdens URI och värdet. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&, const String\&) | Skriver ett element med det angivna prefixet, lokala namnet, namnrymdens URI och värdet. |
| virtual [WriteEndAttribute](./writeendattribute/)() | När den åsidosätts i en avledd klass stänger den det föregående anropet XmlWriter::WriteStartAttribute(String,String). |
| virtual [WriteEndDocument](./writeenddocument/)() | När den åsidosätts i en avledd klass stänger den alla öppna element eller attribut och återställer skrivarens tillstånd till Start. |
| virtual [WriteEndElement](./writeendelement/)() | När den åsidosätts i en avledd klass stänger den ett element och tar bort motsvarande namnrymdsomfång. |
| virtual [WriteEntityRef](./writeentityref/)(const String\&) | När den åsidosätts i en avledd klass skriver den ut en entitetsreferens som **&name**;. |
| virtual [WriteFullEndElement](./writefullendelement/)() | När den åsidosätts i en avledd klass stänger den ett element och tar bort motsvarande namnrymdsomfång. |
| virtual [WriteName](./writename/)(const String\&) | När den åsidosätts i en avledd klass skriver den ut det angivna namnet och säkerställer att det är ett giltigt namn enligt W3C XML 1.0-rekommendationen ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNmToken](./writenmtoken/)(const String\&) | När den åsidosätts i en avledd klass skriver den ut det angivna namnet och säkerställer att det är en giltig NmToken enligt W3C XML 1.0-rekommendationen ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNode](./writenode/)(SharedPtr\<XmlReader\>, bool) | När den åsidosätts i en avledd klass kopierar den allt från läsaren till skrivaren och flyttar läsaren till början av nästa syskon. |
| virtual [WriteNode](./writenode/)(SharedPtr\<XPath::XPathNavigator\>, bool) | Kopierar allt från XPathNavigator-objektet till skrivaren. Positionen för XPathNavigator förblir oförändrad. |
| virtual [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) | När den åsidosätts i en avledd klass skriver den ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: **<?name text?>**. |
| virtual [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den ut det namn som är namnrymdskvalificerat. Denna metod söker upp prefixet som är i räckhåll för den angivna namnrymden. |
| virtual [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | När den åsidosätts i en avledd klass skriver den rå markup manuellt från en teckenbuffert. |
| virtual [WriteRaw](./writeraw/)(const String\&) | När den åsidosätts i en avledd klass skriver den rå markup manuellt från en sträng. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&) | Skriver början av ett attribut med det angivna lokala namnet och namnrymds-URI:n. |
| virtual [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den början av ett attribut med det angivna prefixet, lokala namnet och namnrymds-URI:n. |
| [WriteStartAttribute](./writestartattribute/)(const String\&) | Skriver början av ett attribut med det angivna lokala namnet. |
| virtual [WriteStartDocument](./writestartdocument/)() | När den åsidosätts i en avledd klass skriver den XML-deklarationen med versionen "1.0". |
| virtual [WriteStartDocument](./writestartdocument/)(bool) | När den åsidosätts i en avledd klass skriver den XML-deklarationen med versionen "1.0" och attributet standalone. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den den angivna starttaggen och associerar den med den givna namnrymden. |
| virtual [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) | När den åsidosätts i en avledd klass skriver den den angivna starttaggen och associerar den med den givna namnrymden och prefixet. |
| [WriteStartElement](./writestartelement/)(const String\&) | När den åsidosätts i en avledd klass skriver den ut en starttagg med det angivna lokala namnet. |
| virtual [WriteString](./writestring/)(const String\&) | När den åsidosätts i en avledd klass skriver den den angivna textinnehållet. |
| virtual [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | När den åsidosätts i en avledd klass genererar och skriver den surrogate-teckenentiteten för surrogate-teckenparet. |
| virtual [WriteValue](./writevalue/)(SharedPtr\<Object\>) | Skriver objektvärdet. |
| virtual [WriteValue](./writevalue/)(const String\&) | Skriver ett [String](../../system/string/) värde. |
| virtual [WriteValue](./writevalue/)(bool) | Skriver ett [Boolean](../../system/boolean/) värde. |
| virtual [WriteValue](./writevalue/)(DateTime) | Skriver ett [DateTime](../../system/datetime/) värde. |
| virtual [WriteValue](./writevalue/)(DateTimeOffset) | Skriver ett [DateTimeOffset](../../system/datetimeoffset/) värde. |
| virtual [WriteValue](./writevalue/)(double) | Skriver ett [Double](../../system/double/) värde. |
| virtual [WriteValue](./writevalue/)(float) | Skriver ett enkelprecisionsflyttal. |
| virtual [WriteValue](./writevalue/)(Decimal) | Skriver ett [Decimal](../../system/decimal/) värde. |
| virtual [WriteValue](./writevalue/)(int32_t) | Skriver ett [Int32](../../system/int32/) värde. |
| virtual [WriteValue](./writevalue/)(int64_t) | Skriver ett [Int64](../../system/int64/) värde. |
| virtual [WriteWhitespace](./writewhitespace/)(String) | När den åsidosätts i en avledd klass, skriver ut det givna mellanslaget. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
