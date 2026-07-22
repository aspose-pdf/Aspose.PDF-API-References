---
title: "System::Xml::Schema::XmlAtomicValue klass"
linktitle: "XmlAtomicValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlAtomicValue klass. Representerar det typade värdet av ett validerat XML-element eller attribut. Klassen XmlAtomicValue kan inte ärvas i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue class


Representerar det typade värdet av ett validerat XML-element eller attribut. Klassen [XmlAtomicValue](./) kan inte ärvas.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() | Returnerar en kopia av detta [XmlAtomicValue](./)-objekt. |
| [get_IsNode](./get_isnode/)() override | Returnerar ett värde som indikerar om det validerade XML-elementet eller attributet är en [XPath](../../system.xml.xpath/)-nod eller ett atomärt värde. |
| [get_TypedValue](./get_typedvalue/)() override | Returnerar det aktuella validerade XML-elementet eller attributet som ett boxat objekt av den mest lämpliga typen enligt dess schematyp. |
| [get_Value](./get_value/)() override | Returnerar [String](../../system/string/)-värdet för det validerade XML-elementet eller attributet. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Returnerar det validerade XML-elementets eller attributets värde som en [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Returnerar typen för det validerade XML-elementet eller attributet. |
| [get_XmlType](./get_xmltype/)() override | Returnerar [XmlSchemaType](../xmlschematype/) för det validerade XML-elementet eller attributet. |
| [ToString](./tostring/)() const override | Returnerar [String](../../system/string/)-värdet för det validerade XML-elementet eller attributet. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Returnerar det validerade XML-elementets eller attributets värde som den typ som anges med hjälp av [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet som specificerats för att lösa namnrymdsprefix. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XPathItem](../../system.xml.xpath/xpathitem/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
