---
title: "System::Xml::Schema::XmlSchemaCollection klass"
linktitle: "XmlSchemaCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaCollection klass. Innehåller en cache av XML Schema definition language (XSD) och XML-Data Reduced (XDR)-scheman i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml.schema/xmlschemacollection/
---
## XmlSchemaCollection class


Innehåller en cache av XML [Schema](../) definitionsspråk (XSD) och XML-Data Reduced (XDR) scheman.

```cpp
class XmlSchemaCollection : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Lägger till schemat som finns på den angivna URL:en i schemasamlingen. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&) | Lägger till schemat som finns i [XmlReader](../../system.xml/xmlreader/) till schemasamlingen. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Lägger till schemat som finns i [XmlReader](../../system.xml/xmlreader/) till schemasamlingen. Den angivna [XmlResolver](../../system.xml/xmlresolver/) används för att lösa eventuella externa resurser. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Lägger till [XmlSchema](../xmlschema/) i samlingen. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Lägger till [XmlSchema](../xmlschema/) i samlingen. Den angivna [XmlResolver](../../system.xml/xmlresolver/) används för att lösa eventuella externa referenser. |
| [Add](./add/)(const SharedPtr\<XmlSchemaCollection\>\&) | Lägger till alla namnrymder som definierats i den angivna samlingen (inklusive deras associerade scheman) till denna samling. |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Returnerar ett värde som indikerar om **targetNamespace** för den angivna [XmlSchema](../xmlschema/) finns i samlingen. |
| [Contains](./contains/)(const String\&) | Returnerar ett värde som indikerar om ett schema med den angivna namnrymden finns i samlingen. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Kopierar alla [XmlSchema](../xmlschema/)‑objekt från denna samling till den angivna arrayen med start vid det angivna indexet. |
| [get_Count](./get_count/)() | Returnerar antalet namnrymder som definierats i denna samling. |
| [get_NameTable](./get_nametable/)() | Returnerar standard‑[XmlNameTable](../../system.xml/xmlnametable/) som används av [XmlSchemaCollection](./) när nya scheman laddas. |
| [GetEnumerator](./getenumerator/)() override | Tillhandahåller stöd för iteration över samlingen av scheman. |
| [idx_get](./idx_get/)(const String\&) | Returnerar [XmlSchema](../xmlschema/) som är associerad med den angivna namnrymdens URI. |
| [XmlSchemaCollection](./xmlschemacollection/)() | Initierar en ny instans av klassen [XmlSchemaCollection](./). |
| [XmlSchemaCollection](./xmlschemacollection/)(const SharedPtr\<XmlNameTable\>\&) | Initierar en ny instans av klassen [XmlSchemaCollection](./) med den angivna [XmlNameTable](../../system.xml/xmlnametable/). [XmlNameTable](../../system.xml/xmlnametable/) används när scheman laddas. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar


## Deprecated
Klassen XmlSchemaCollection är föråldrad. Använd XmlSchemaSet istället.

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
