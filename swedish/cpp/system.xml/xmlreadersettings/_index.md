---
title: "System::Xml::XmlReaderSettings klass"
linktitle: "XmlReaderSettings"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReaderSettings klass. Anger en uppsättning funktioner som ska stödjas på XmlReader-objektet som skapas av XmlReader::Create‑metoden i C++."
type: docs
weight: 3400
url: /sv/cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


Anger en uppsättning funktioner som ska stödjas på [XmlReader](../xmlreader/)‑objektet som skapas av [XmlReader::Create](../xmlreader/create/)‑metoden.

```cpp
class XmlReaderSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CheckReadOnly](./checkreadonly/)(const String\&) |  |
| [Clone](./clone/)() | Skapar en kopia av [XmlReaderSettings](./)-instansen. |
| [get_CheckCharacters](./get_checkcharacters/)() | Returnerar ett värde som indikerar om teckenkontroll ska utföras. |
| [get_CloseInput](./get_closeinput/)() | Returnerar ett värde som indikerar om den underliggande strömmen eller TextReader ska stängas när läsaren stängs. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Returnerar den efterlevnadsnivå som [XmlReader](../xmlreader/) kommer att följa. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Returnerar ett värde som bestämmer bearbetningen av DTD:er. |
| [get_IgnoreComments](./get_ignorecomments/)() | Returnerar ett värde som indikerar om kommentarer ska ignoreras. |
| [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Returnerar ett värde som indikerar om bearbetningsinstruktioner ska ignoreras. |
| [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Returnerar ett värde som indikerar om insignifikant blanksteg ska ignoreras. |
| [get_LineNumberOffset](./get_linenumberoffset/)() | Returnerar radnummerförskjutning för [XmlReader](../xmlreader/)-objektet. |
| [get_LinePositionOffset](./get_linepositionoffset/)() | Returnerar radpositionsförskjutning för [XmlReader](../xmlreader/)-objektet. |
| [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Returnerar ett värde som anger det maximalt tillåtna antalet tecken i ett dokument som resultat av att expandera enheter. |
| [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Returnerar ett värde som anger det maximalt tillåtna antalet tecken i ett XML-dokument. Ett nollvärde (0) betyder att det inte finns några begränsningar för XML-dokumentets storlek. Ett icke-nollvärde specificerar den maximala storleken i tecken. |
| [get_NameTable](./get_nametable/)() | Returnerar den [XmlNameTable](../xmlnametable/) som används för atomiserade strängjämförelser. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Returnerar ett värde som indikerar om bearbetning av dokumenttypdefinition (DTD) ska förbjudas. |
| [get_Schemas](./get_schemas/)() | Returnerar XmlSchemaSet som ska användas vid schemavalidering. |
| [get_ValidationFlags](./get_validationflags/)() | Returnerar ett värde som indikerar schemavalideringsinställningarna. Denna inställning gäller för [XmlReader](../xmlreader/)-objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](./get_validationtype/)-värdet är [ValidationType::Schema](../validationtype/)). |
| [get_ValidationType](./get_validationtype/)() | Returnerar ett värde som indikerar om [XmlReader](../xmlreader/) kommer att utföra validering eller typtilldelning vid läsning. |
| [Reset](./reset/)() | Återställer medlemmarna i inställningsklassen till deras standardvärden. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Ställer in ett värde som indikerar om teckenkontroll ska utföras. |
| [set_CloseInput](./set_closeinput/)(bool) | Ställer in ett värde som indikerar om den underliggande strömmen eller TextReader ska stängas när läsaren stängs. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Ställer in den efterlevnadsnivå som [XmlReader](../xmlreader/) ska följa. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Ställer in ett värde som bestämmer bearbetningen av DTD:er. |
| [set_IgnoreComments](./set_ignorecomments/)(bool) | Ställer in ett värde som indikerar om kommentarer ska ignoreras. |
| [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(bool) | Ställer in ett värde som indikerar om bearbetningsinstruktioner ska ignoreras. |
| [set_IgnoreWhitespace](./set_ignorewhitespace/)(bool) | Ställer in ett värde som indikerar om insignifikant blanksteg ska ignoreras. |
| [set_LineNumberOffset](./set_linenumberoffset/)(int32_t) | Ställer in radnummerförskjutning för [XmlReader](../xmlreader/)-objektet. |
| [set_LinePositionOffset](./set_linepositionoffset/)(int32_t) | Ställer in radpositionsförskjutning för [XmlReader](../xmlreader/)‑objektet. |
| [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(int64_t) | Ställer in ett värde som anger det maximalt tillåtna antalet tecken i ett dokument som resultat av att expandera entiteter. |
| [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(int64_t) | Ställer in ett värde som anger det maximalt tillåtna antalet tecken i ett XML‑dokument. Ett nollvärde (0) betyder att det inte finns några begränsningar för XML‑dokumentets storlek. Ett icke‑nollvärde anger den maximala storleken i tecken. |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Ställer in [XmlNameTable](../xmlnametable/) som används för atomiserade strängjämförelser. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Ställer in ett värde som anger om dokumenttypdefinition (DTD)‑behandling ska förbjudas. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Ställer in XmlSchemaSet som ska användas vid schemavalidering. |
| [set_ValidationFlags](./set_validationflags/)(Schema::XmlSchemaValidationFlags) | Ställer in ett värde som anger schemavalideringsinställningarna. Denna inställning gäller för [XmlReader](../xmlreader/)‑objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](./get_validationtype/)‑värdet är [ValidationType::Schema](../validationtype/)). |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Ställer in ett värde som anger om [XmlReader](../xmlreader/) ska utföra validering eller typtilldelning vid läsning. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in [XmlResolver](../xmlresolver/) som används för att komma åt externa dokument. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Lägger till en händelsehanterare som körs när läsaren stöter på valideringsfel. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Tar bort en händelsehanterare som körs när läsaren stöter på valideringsfel. |
| [XmlReaderSettings](./xmlreadersettings/)() | Initierar en ny instans av klassen [XmlReaderSettings](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
