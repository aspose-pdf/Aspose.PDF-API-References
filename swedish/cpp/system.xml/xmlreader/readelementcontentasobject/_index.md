---
title: "System::Xml::XmlReader::ReadElementContentAsObject metod"
linktitle: "ReadElementContentAsObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::ReadElementContentAsObject metod. Läser det aktuella elementet och returnerar innehållet som ett Object i C++."
type: docs
weight: 6200
url: /sv/cpp/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Läser det aktuella elementet och returnerar innehållet som ett [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### ReturnValue

Ett inneslutet objekt av den mest lämpliga typen. Värdet från [XmlReader::get_ValueType](../get_valuetype/) bestämmer den lämpliga typen. Om innehållet är typat som en listtyp returnerar denna metod en array av inneslutna objekt av den lämpliga typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAsObject(String, String) method


Kontrollerar att det angivna lokala namnet och namnrymds-URI:n matchar den för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | Det lokala namnet på elementet. |
| namespaceURI | String | Namnrymdens URI för elementet. |

### ReturnValue

Ett inneslutet objekt av den mest lämpliga typen. Värdet från [XmlReader::get_ValueType](../get_valuetype/) bestämmer den lämpliga typen. Om innehållet är typat som en listtyp returnerar denna metod en array av inneslutna objekt av den lämpliga typen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
