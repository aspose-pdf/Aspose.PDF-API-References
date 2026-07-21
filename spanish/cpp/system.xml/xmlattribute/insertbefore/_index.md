---
title: "System::Xml::XmlAttribute::InsertBefore método"
linktitle: "InsertBefore"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttribute::InsertBefore método. Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore method


Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | El [XmlNode](../../xmlnode/) a insertar. |
| refChild | SharedPtr\<XmlNode\> | El [XmlNode](../../xmlnode/) que es el nodo de referencia. El **newChild** se coloca antes de este nodo. |

### ReturnValue

El [XmlNode](../../xmlnode/) insertado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
