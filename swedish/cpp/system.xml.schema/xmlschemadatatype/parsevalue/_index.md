---
title: "System::Xml::Schema::XmlSchemaDatatype::ParseValue method"
linktitle: "ParseValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaDatatype::ParseValue‑metod. När den åsidosätts i en avledd klass validerar den den angivna strängen mot en inbyggd eller användardefinierad enkel typ i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue method


När den åsidosätts i en avledd klass, validerar den den angivna **string** mot en inbyggd eller användardefinierad enkel typ.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Den **string** som ska valideras mot den enkla typen. |
| nameTable | SharedPtr\<XmlNameTable\> | Den [XmlNameTable](../../../system.xml/xmlnametable/) som ska användas för atomisering vid parsning av **string** om detta [XmlSchemaDatatype](../)-objekt representerar **xs:NCName**-typen. |
| nsmgr | SharedPtr\<IXmlNamespaceResolver\> | Det [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-objekt som ska användas vid parsning av **string** om detta [XmlSchemaDatatype](../)-objekt representerar **xs:QName**-typen. |

### ReturnValue

Ett [Object](../../../system/object/) som säkert kan kastas till den typ som returneras av anropet [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
