---
title: "Método InsertBefore de System::Xml::XmlAttributeCollection"
linktitle: "InsertBefore"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método InsertBefore de System::Xml::XmlAttributeCollection. Inserta el atributo especificado inmediatamente antes del atributo de referencia especificado en C++."
type: docs
weight: 500
url: /es/cpp/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore method


Inserta el atributo especificado inmediatamente antes del atributo de referencia especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newNode | const SharedPtr\<XmlAttribute\>\& | El atributo a insertar. |
| refNode | const SharedPtr\<XmlAttribute\>\& | El atributo de referencia. **newNode** se coloca antes del **refNode**. |

### ReturnValue

El [XmlAttribute](../../xmlattribute/) para insertar en la colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
