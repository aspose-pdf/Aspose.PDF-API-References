---
title: "System::Xml::XmlTextWriter class"
linktitle: "XmlTextWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextWriter class. Representerar en skribent som tillhandahåller ett snabbt, icke-cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data som följer W3C:s Extensible Markup Language (XML) 1.0 och rekommendationerna för Namespaces in XML i C++."
type: docs
weight: 4000
url: /sv/cpp/system.xml/xmltextwriter/
---
## XmlTextWriter class


Representerar en skrivare som ger ett snabbt, icke‑cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML‑data som följer W3C:s Extensible Markup Language (XML) 1.0 och rekommendationerna för Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger denna ström och den underliggande strömmen. |
| [Flush](./flush/)() override | Spolar allt som finns i bufferten till de underliggande strömmarna och spolar även den underliggande strömmen. |
| [get_BaseStream](./get_basestream/)() | Returnerar det underliggande strömobjektet. |
| [get_Formatting](./get_formatting/)() | Anger hur utdata är formaterad. |
| [get_Indentation](./get_indentation/)() | Returnerar hur många IndentChars som ska skrivas för varje nivå i hierarkin när [XmlTextWriter::set_Formatting](./set_formatting/) är inställd på [Formatting::Indented](../formatting/). |
| [get_IndentChar](./get_indentchar/)() | Returnerar vilket tecken som ska användas för indentering när [XmlTextWriter::set_Formatting](./set_formatting/) är inställt på [Formatting::Indented](../formatting/). |
| [get_Namespaces](./get_namespaces/)() | Returnerar ett värde som indikerar om namnrymdsstöd ska användas. |
| [get_QuoteChar](./get_quotechar/)() | Returnerar vilket tecken som ska användas för att citera attributvärden. |
| [get_WriteState](./get_writestate/)() override | Returnerar skrivarens tillstånd. |
| [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [get_XmlSpace](./get_xmlspace/)() override | Returnerar ett [XmlSpace](../xmlspace/) som representerar det aktuella **xml:space**-omfånget. |
| [LookupPrefix](./lookupprefix/)(String) override | Returnerar det närmaste prefixet som definierats i det aktuella namnrymdsomfånget för namnrymdens URI. |
| [set_Formatting](./set_formatting/)(System::Xml::Formatting) | Anger hur utdata är formaterad. |
| [set_Indentation](./set_indentation/)(int32_t) | Ställer in hur många IndentChars som ska skrivas för varje nivå i hierarkin när [XmlTextWriter::set_Formatting](./set_formatting/) är inställd på [Formatting::Indented](../formatting/). |
| [set_IndentChar](./set_indentchar/)(char16_t) | Ställer in vilket tecken som ska användas för indentering när [XmlTextWriter::set_Formatting](./set_formatting/) är inställt på [Formatting::Indented](../formatting/). |
| [set_Namespaces](./set_namespaces/)(bool) | Ställer in ett värde som indikerar om namnrymdsstöd ska användas. |
| [set_QuoteChar](./set_quotechar/)(char16_t) | Ställer in vilket tecken som ska användas för att citera attributvärden. |
| [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Kodar de angivna binära bytena som base64 och skriver ut den resulterande texten. |
| [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Kodar de angivna binära bytena som binhex och skriver ut den resulterande texten. |
| [WriteCData](./writecdata/)(String) override | Skriver ut ett **...**-block som innehåller den angivna texten. |
| [WriteCharEntity](./writecharentity/)(char16_t) override | Tvingar fram generering av en teckenentity för det angivna Unicode-teckenvärdet. |
| [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Skriver text en buffer åt gången. |
| [WriteComment](./writecomment/)(String) override | Skriver ut en kommentar **** som innehåller den angivna texten. |
| [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) override | Skriver DOCTYPE-deklarationen med det angivna namnet och valfria attribut. |
| [WriteEndAttribute](./writeendattribute/)() override | Stänger det föregående anropet till [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| [WriteEndDocument](./writeenddocument/)() override | Stänger alla öppna element eller attribut och återställer skrivarens tillstånd till Start. |
| [WriteEndElement](./writeendelement/)() override | Stänger ett element och poppar det motsvarande namnrymdsomfånget. |
| [WriteEntityRef](./writeentityref/)(const String\&) override | Skriver ut en enhetsreferens som **&name**;. |
| [WriteFullEndElement](./writefullendelement/)() override | Stänger ett element och poppar det motsvarande namnrymdsomfånget. |
| [WriteName](./writename/)(const String\&) override | Skriver ut det angivna namnet och säkerställer att det är ett giltigt namn enligt [W3C XML 1.0-rekommendationen](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteNmToken](./writenmtoken/)(const String\&) override | Skriver ut det angivna namnet och säkerställer att det är ett giltigt **NmToken** enligt [W3C XML 1.0-rekommendationen](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) override | Skriver ut en processinstruktion med ett mellanslag mellan namn och text enligt följande: **<?name text?>**. |
| [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) override | Skriver ut det namnrymdskvalificerade namnet. Denna metod letar upp prefixet som är i räckhåll för den angivna namnrymden. |
| [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Skriver rå markup manuellt från en teckenbuffert. |
| [WriteRaw](./writeraw/)(const String\&) override | Skriver rå markup manuellt från en sträng. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) override | Skriver början av ett attribut. |
| [WriteStartDocument](./writestartdocument/)() override | Skriver XML-deklarationen med versionen "1.0". |
| [WriteStartDocument](./writestartdocument/)(bool) override | Skriver XML-deklarationen med versionen "1.0" och standalone-attributet. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) override | Skriver den angivna starttaggen och associerar den med den givna namnrymden och prefixet. |
| [WriteString](./writestring/)(const String\&) override | Skriver den angivna textinnehållet. |
| [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genererar och skriver surrogate-teckenentiteten för surrogate-teckenparet. |
| [WriteWhitespace](./writewhitespace/)(String) override | Skriver ut det angivna mellanslaget. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Skapar en instans av klassen [XmlTextWriter](./) med den angivna strömmen och kodningen. |
| [XmlTextWriter](./xmltextwriter/)(const String\&, const SharedPtr\<Text::Encoding\>\&) | Skapar en instans av klassen [XmlTextWriter](./) med den angivna filen. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::TextWriter\>\&) | Skapar en instans av klassen [XmlTextWriter](./) med den angivna TextWriter. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Det rekommenderas att använda klassen [XmlWriter](../xmlwriter/) istället.

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
