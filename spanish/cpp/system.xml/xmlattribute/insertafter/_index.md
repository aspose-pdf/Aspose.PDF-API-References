---
title: "System::Xml::XmlAttribute::InsertAfter método"
linktitle: "InsertAfter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttribute::InsertAfter método. Inserta el nodo especificado inmediatamente después del nodo de referencia especificado en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter method


Inserta el nodo especificado inmediatamente después del nodo de referencia especificado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newChild | SharedPtr\<XmlNode\> | El [XmlNode](../../xmlnode/) a insertar. |
| refChild | SharedPtr\<XmlNode\> | El [XmlNode](../../xmlnode/) que es el nodo de referencia. El **newChild** se coloca después del **refChild**. |

### ReturnValue

El [XmlNode](../../xmlnode/) insertado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
