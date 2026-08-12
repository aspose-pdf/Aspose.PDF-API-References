---
title: "System::Xml::Schema::XmlSchemaType-klass"
linktitle: "XmlSchemaType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaType-klass. Bas-klassen för alla enkla typer och komplexa typer i C++."
type: docs
weight: 6800
url: /sv/cpp/system.xml.schema/xmlschematype/
---
## XmlSchemaType class


Basklassen för alla enkla typer och komplexa typer.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BaseSchemaType](./get_baseschematype/)() | Returnerar post-kompileringens objekttyp eller den inbyggda XML [Schema](../) Definition Language (XSD)-datatypen, simpleType‑elementet eller complexType‑elementet. Detta är ett post‑schema‑kompileringens informationsuppsättningsvärde. |
| [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Returnerar post‑kompileringens värde för basklassen för denna schematyp. |
| [get_Datatype](./get_datatype/)() | Returnerar post‑kompileringens värde för datatypen för den komplexa typen. |
| [get_DerivedBy](./get_derivedby/)() | Returnerar post‑kompileringens information om hur detta element härstammar från sin basklass. |
| [get_Final](./get_final/)() | Returnerar det slutgiltiga attributet för typderivationen som anger om ytterligare derivationer är tillåtna. |
| [get_FinalResolved](./get_finalresolved/)() | Returnerar post‑kompileringens tolkning av värdet [XmlSchemaType::get_Final](./get_final/). |
| virtual [get_IsMixed](./get_ismixed/)() | Returnerar ett värde som indikerar om denna typ har en blandad innehållsmodell. Detta anrop är endast giltigt i en komplex typ. |
| [get_Name](./get_name/)() | Returnerar typens namn. |
| [get_QualifiedName](./get_qualifiedname/)() | Returnerar det kvalificerade namnet för typen som byggts från **Name**‑attributet för denna typ. Detta är ett post‑schema‑kompileringens värde. |
| [get_TypeCode](./get_typecode/)() | Returnerar [XmlTypeCode](../xmltypecode/) för typen. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(XmlTypeCode) | Returnerar en [XmlSchemaComplexType](../xmlschemacomplextype/) som representerar den inbyggda komplexa typen för den specificerade komplexa typen. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(const SharedPtr\<XmlQualifiedName\>\&) | Returnerar en [XmlSchemaComplexType](../xmlschemacomplextype/) som representerar den inbyggda komplexa typen för den komplexa typen som specificerats med kvalificerat namn. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const SharedPtr\<XmlQualifiedName\>\&) | Returnerar en [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den enkla typen som specificerats med det kvalificerade namnet. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(XmlTypeCode) | Returnerar en [XmlSchemaSimpleType](../xmlschemasimpletype/) som representerar den inbyggda enkla typen för den specificerade enkla typen. |
| static [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) | Returnerar ett värde som indikerar om den specificerade avledda schematypen är avledd från den specificerade bas‑schematypen. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Ställer in det slutgiltiga attributet för typavledningen som indikerar om ytterligare avledningar är tillåtna. |
| virtual [set_IsMixed](./set_ismixed/)(bool) | Ställer in ett värde som indikerar om denna typ har en blandad innehållsmodell. Detta anrop är endast giltigt i en komplex typ. |
| [set_Name](./set_name/)(const String\&) | Ställer in namnet på typen. |
| [XmlSchemaType](./xmlschematype/)() | Initierar en ny instans av klassen [XmlSchemaType](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
