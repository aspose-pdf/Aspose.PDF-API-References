---
title: "System::Xml::XmlNode::get_ParentNode método"
linktitle: "get_ParentNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNode::get_ParentNode método. Devuelve el padre de este nodo (para nodos que pueden tener padres) en C++."
type: docs
weight: 2100
url: /es/cpp/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode method


Devuelve el padre de este nodo (para nodos que pueden tener padres).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### ReturnValue

El [XmlNode](../) que es el padre del nodo actual.
## Observaciones



Si un nodo acaba de ser creado y aún no se ha añadido al árbol, o si ha sido eliminado del árbol, el padre es **nullptr**. Para todos los demás nodos, el valor devuelto depende del [XmlNode::get_NodeType](../get_nodetype/) del nodo. La tabla siguiente describe los posibles valores de retorno del método **get_NodeType**. |||
|-|-|
| NodeType | Valor de retorno de ParentNode |
| Attribute, Document, DocumentFragment, Entity, Notation | Devuelve nullptr; estos nodos no tienen padres. |
| CDATA | Devuelve el elemento o la referencia de entidad que contiene la sección CDATA. |
| Comment | Devuelve el elemento, la referencia de entidad, el tipo de documento o el documento que contiene el comentario. |
| DocumentType | Devuelve el nodo del documento. |
| Elemento | Devuelve el nodo padre del elemento. Si el elemento es el nodo raíz en el árbol, el padre es el nodo del documento. |
| EntityReference | Devuelve el elemento, atributo o referencia de entidad que contiene la referencia de entidad. |
| ProcessingInstruction | Devuelve el documento, elemento, tipo de documento o referencia de entidad que contiene la instrucción de procesamiento. |
| Text | Devuelve el elemento padre, atributo o referencia de entidad que contiene el nodo de texto. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
