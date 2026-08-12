---
title: "System::Xml::Schema::XmlSchemaDatatype‑klass"
linktitle: "XmlSchemaDatatype"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaDatatype‑klass. XmlSchemaDatatype‑klassen är en abstrakt klass för att mappa XML Schema definition language (XSD)-typer till körningstyper i C++."
type: docs
weight: 2400
url: /sv/cpp/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype class


[XmlSchemaDatatype](./)-klassen är en abstrakt klass för att mappa XML [Schema](../) definition language (XSD)-typer till körningstyper.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&) | Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML‑schematypen som representeras av [XmlSchemaDatatype](./), till den angivna körningstypen. |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML‑schematypen som representeras av [XmlSchemaDatatype](./), till den angivna körningstypen med hjälp av [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) om [XmlSchemaDatatype](./) representerar **xs:QName**‑typen eller en typ som är härledd från den. |
| virtual [get_TokenizedType](./get_tokenizedtype/)() | När den åsidosätts i en avledd klass, hämtar den typen för **string** enligt specifikationen för World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0. |
| virtual [get_TypeCode](./get_typecode/)() | Returnerar [XmlTypeCode](../xmltypecode/)-värdet för den enkla typen. |
| virtual [get_ValueType](./get_valuetype/)() | När den åsidosätts i en avledd klass, hämtar den typen av objektet. |
| virtual [get_Variety](./get_variety/)() | Returnerar [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/)-värdet för den enkla typen. |
| virtual [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaDatatype\>) | Denna metod returnerar alltid **false**. |
| virtual [ParseValue](./parsevalue/)(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) | När den åsidosätts i en avledd klass, validerar den den angivna **string** mot en inbyggd eller användardefinierad enkel typ. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
