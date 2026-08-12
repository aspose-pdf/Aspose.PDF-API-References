---
title: "System::Xml::XPath::XPathItem klass"
linktitle: "XPathItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathItem klass. Representerar ett objekt i XQuery 1.0 och XPath 2.0 datamodellen i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.xpath/xpathitem/
---
## XPathItem class


Representerar ett objekt i XQuery 1.0 och [XPath](../) 2.0 [Data](../../system.data/) Modell.

```cpp
class XPathItem : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_IsNode](./get_isnode/)() | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om objektet representerar en [XPath](../) nod eller ett atomärt värde. |
| virtual [get_TypedValue](./get_typedvalue/)() | När den åsidosätts i en avledd klass, hämtar det aktuella objektet som ett inbäddat objekt av den mest lämpliga typen enligt dess schematyp. |
| virtual [get_Value](./get_value/)() | När den åsidosätts i en avledd klass, hämtar **string**-värdet för objektet. |
| virtual [get_ValueAsBoolean](./get_valueasboolean/)() | När den åsidosätts i en avledd klass, hämtar objektets värde som en [Boolean](../../system/boolean/). |
| virtual [get_ValueAsDateTime](./get_valueasdatetime/)() | När den åsidosätts i en avledd klass, hämtar objektets värde som en [DateTime](../../system/datetime/). |
| virtual [get_ValueAsDouble](./get_valueasdouble/)() | När den åsidosätts i en avledd klass, hämtar objektets värde som en [Double](../../system/double/). |
| virtual [get_ValueAsInt](./get_valueasint/)() | När den åsidosätts i en avledd klass, hämtar objektets värde som en [Int32](../../system/int32/). |
| virtual [get_ValueAsLong](./get_valueaslong/)() | När den åsidosätts i en avledd klass, hämtar objektets värde som en [Int64](../../system/int64/). |
| virtual [get_ValueType](./get_valuetype/)() | När den åsidosätts i en avledd klass, hämtar den typen av objektet. |
| virtual [get_XmlType](./get_xmltype/)() | När den åsidosätts i en avledd klass, hämtar XmlSchemaType för objektet. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&) | Returnerar objektets värde som den angivna typen. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | När den åsidosätts i en avledd klass returnerar den objektets värde som den typ som anges med hjälp av [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)‑objektet som specificeras för att lösa namnrymdsprefix. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
