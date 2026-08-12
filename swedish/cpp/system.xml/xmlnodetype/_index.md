---
title: "System::Xml::XmlNodeType enum"
linktitle: "XmlNodeType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeType enum. Anger typen av nod i C++."
type: docs
weight: 6200
url: /sv/cpp/system.xml/xmlnodetype/
---
## XmlNodeType enum


Anger nodens typ.

```cpp
enum class XmlNodeType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Detta returneras av [XmlReader](../xmlreader/) om en **Read**‑metod inte har anropats. |
| Element | 1 | Ett element (till exempel **<item>**). |
| Attribute | 2 | Ett attribut (till exempel **id='123'**). |
| Text | 3 | Textinnehållet i en nod. En [XmlNodeType::Text](./)‑nod kan inte ha några barnnoder. Den kan förekomma som barnnod till [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) och [XmlNodeType::EntityReference](./) noder. |
| CDATA | 4 | En CDATA-sektion (till exempel **my escaped text**). |
| EntityReference | 5 | En referens till en entitet (till exempel, **&num;**). |
| Entity | 6 | En entitetsdeklaration (till exempel, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | En bearbetningsinstruktion (till exempel, **<?pi test?>**). |
| Comment | 8 | En kommentar (till exempel, ****). |
| Document | 9 | Ett dokumentobjekt som, som roten i dokumentträdet, ger åtkomst till hela XML-dokumentet. |
| DocumentType | 10 | Dokumenttypdeklarationen, som indikeras av följande tagg (till exempel, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Ett dokumentfragment. |
| Notation | 12 | En notation i dokumenttypdeklarationen (till exempel, **<!NOTATION...>**). |
| Whitespace | 13 | Mellanslag mellan markup. |
| SignificantWhitespace | 14 | Mellanslag mellan markup i en blandad innehållsmodell eller mellanslag inom **xml:space=\"preserve\"**-området. |
| EndElement | 15 | En slut-elementtagg (till exempel, ****). |
| EndEntity | 16 | Returneras när [XmlReader](../xmlreader/) når slutet av entitetsersättningen som ett resultat av ett anrop till [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | XML-deklarationen (till exempel, **<?xml version='1.0'?>**). Noden [XmlNodeType::XmlDeclaration](./) måste vara den första noden i dokumentet. Den kan inte ha barn. Den är ett barn till noden [XmlNodeType::Document](./). Den kan ha attribut som tillhandahåller versions- och kodningsinformation. |

## Se även

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
