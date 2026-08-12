---
title: "System::Xml::Schema::XmlSchemaSet klass"
linktitle: "XmlSchemaSet"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaSet klass. Innehåller en cache av XML Schema definition language (XSD)-scheman i C++."
type: docs
weight: 5800
url: /sv/cpp/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet class


Innehåller en cache av XML [Schema](../) definition language (XSD)-scheman.

```cpp
class XmlSchemaSet : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(String, const String\&) | Lägger till XML [Schema](../) definition language (XSD)-schemat på den angivna URL:en till [XmlSchemaSet](./). |
| [Add](./add/)(String, const SharedPtr\<XmlReader\>\&) | Lägger till XML [Schema](../) definition language (XSD)-schemat som finns i [XmlReader](../../system.xml/xmlreader/) till [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchemaSet\>\&) | Lägger till alla XML [Schema](../) definition language (XSD)-scheman i den angivna [XmlSchemaSet](./) till [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Lägger till den angivna [XmlSchema](../xmlschema/) till [XmlSchemaSet](./). |
| [Compile](./compile/)() | Kompilerar de XML [Schema](../) definition language (XSD)-scheman som lagts till i [XmlSchemaSet](./) till ett logiskt schema. |
| [Contains](./contains/)(String) | Anger om ett XML [Schema](../) definition language (XSD)-schema med den specificerade mål‑namnrymdens URI finns i [XmlSchemaSet](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Anger om det specificerade XML [Schema](../) definition language (XSD) [XmlSchema](../xmlschema/)-objektet finns i [XmlSchemaSet](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Kopierar alla [XmlSchema](../xmlschema/)-objekt från [XmlSchemaSet](./) till den angivna arrayen, med start vid det angivna indexet. |
| [get_CompilationSettings](./get_compilationsettings/)() | Returnerar [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) för [XmlSchemaSet](./). |
| [get_Count](./get_count/)() | Returnerar antalet logiska XML [Schema](../) definition language (XSD)-scheman i [XmlSchemaSet](./). |
| [get_GlobalAttributes](./get_globalattributes/)() | Returnerar alla globala attribut i alla XML [Schema](../) definition language (XSD)-scheman i [XmlSchemaSet](./). |
| [get_GlobalElements](./get_globalelements/)() | Returnerar alla globala element i alla XML [Schema](../) definition language (XSD)-scheman i [XmlSchemaSet](./). |
| [get_GlobalTypes](./get_globaltypes/)() | Returnerar alla globala enkla och komplexa typer i alla XML [Schema](../) definition language (XSD)-scheman i [XmlSchemaSet](./). |
| [get_IsCompiled](./get_iscompiled/)() | Returnerar ett värde som indikerar om XML‑[Schema](../) definitionsspråk (XSD)-scheman i [XmlSchemaSet](./) har kompilerats. |
| [get_NameTable](./get_nametable/)() | Returnerar standard‑[XmlNameTable](../../system.xml/xmlnametable/) som används av [XmlSchemaSet](./) när nya XML‑[Schema](../) definitionsspråk (XSD)-scheman läses in. |
| [Remove](./remove/)(const SharedPtr\<XmlSchema\>\&) | Tar bort det angivna XML‑[Schema](../) definitionsspråk (XSD)-schemat från [XmlSchemaSet](./). |
| [RemoveRecursive](./removerecursive/)(const SharedPtr\<XmlSchema\>\&) | Tar bort det angivna XML‑[Schema](../) definitionsspråk (XSD)-schemat och alla scheman som det importerar från [XmlSchemaSet](./). |
| [Reprocess](./reprocess/)(SharedPtr\<XmlSchema\>) | Bearbetar om ett XML‑[Schema](../) definitionsspråk (XSD)-schema som redan finns i [XmlSchemaSet](./). |
| [Schemas](./schemas/)() | Returnerar en samling av alla XML‑[Schema](../) definitionsspråk (XSD)-scheman i [XmlSchemaSet](./). |
| [Schemas](./schemas/)(String) | Returnerar en samling av alla XML‑[Schema](../) definitionsspråk (XSD)-scheman i [XmlSchemaSet](./) som tillhör det angivna namnrymden. |
| [set_CompilationSettings](./set_compilationsettings/)(const SharedPtr\<XmlSchemaCompilationSettings\>\&) | Ställer in [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) för [XmlSchemaSet](./). |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in [XmlResolver](../../system.xml/xmlresolver/) som används för att lösa namnrymder eller platser som refereras i include‑ och import‑element i ett schema. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Lägger till en händelsehanterare för att ta emot information om XML‑[Schema](../) definitionsspråk (XSD)-schemavalideringsfel. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Tar bort en händelsehanterare för att ta emot information om XML‑[Schema](../) definitionsspråk (XSD)-schemavalideringsfel. |
| [XmlSchemaSet](./xmlschemaset/)() | Initierar en ny instans av klassen [XmlSchemaSet](./). |
| [XmlSchemaSet](./xmlschemaset/)(const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlSchemaSet](./) med den angivna [XmlNameTable](../../system.xml/xmlnametable/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
