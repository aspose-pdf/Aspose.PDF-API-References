---
title: "System::Xml::XmlAttributeCollection::InsertAfter método"
linktitle: "InsertAfter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttributeCollection::InsertAfter método. Inserta el atributo especificado inmediatamente después del atributo de referencia especificado en C++."
type: docs
weight: 400
url: /es/cpp/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter method


Inserta el atributo especificado inmediatamente después del atributo de referencia especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | El atributo a insertar. |
| refNode | const SharedPtr\<XmlAttribute\>\& | El atributo de referencia. **newNode** se coloca después del **refNode**. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) para insertar en la colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
