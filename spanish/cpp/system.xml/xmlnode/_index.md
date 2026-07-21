---
title: "Clase System::Xml::XmlNode"
linktitle: "XmlNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlNode. Representa un único nodo en el documento XML en C++."
type: docs
weight: 2500
url: /es/cpp/system.xml/xmlnode/
---
## XmlNode class


Representa un nodo único en el documento XML.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) | Agrega el nodo especificado al final de la lista de nodos hijos de este nodo. |
| virtual [Clone](./clone/)() | Crea un duplicado de este nodo. |
| virtual [CloneNode](./clonenode/)(bool) | Crea un duplicado del nodo, cuando se sobrescribe en una clase derivada. |
| [CreateNavigator](./createnavigator/)() override | Crea un XPathNavigator para navegar este objeto. |
| virtual [get_Attributes](./get_attributes/)() | Devuelve una [XmlAttributeCollection](../xmlattributecollection/) que contiene los atributos de este nodo. |
| virtual [get_BaseURI](./get_baseuri/)() | Devuelve la URI base del nodo actual. |
| virtual [get_ChildNodes](./get_childnodes/)() | Devuelve todos los nodos hijos del nodo. |
| virtual [get_FirstChild](./get_firstchild/)() | Devuelve el primer hijo del nodo. |
| virtual [get_HasChildNodes](./get_haschildnodes/)() | Devuelve un valor que indica si este nodo tiene algún nodo hijo. |
| virtual [get_InnerText](./get_innertext/)() | Devuelve los valores concatenados del nodo y todos sus nodos hijos. |
| virtual [get_InnerXml](./get_innerxml/)() | Devuelve el marcado que representa solo los nodos hijos de este nodo. |
| virtual [get_IsReadOnly](./get_isreadonly/)() | Devuelve un valor que indica si el nodo es de solo lectura. |
| virtual [get_LastChild](./get_lastchild/)() | Devuelve el último hijo del nodo. |
| virtual [get_LocalName](./get_localname/)() | Devuelve el nombre local del nodo, cuando se sobrescribe en una clase derivada. |
| virtual [get_Name](./get_name/)() | Devuelve el nombre calificado del nodo, cuando se sobrescribe en una clase derivada. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Devuelve el URI del espacio de nombres de este nodo. |
| virtual [get_NextSibling](./get_nextsibling/)() | Devuelve el nodo que sigue inmediatamente a este nodo. |
| virtual [get_NodeType](./get_nodetype/)() | Devuelve el tipo del nodo actual, cuando se sobrescribe en una clase derivada. |
| virtual [get_OuterXml](./get_outerxml/)() | Devuelve el marcado que contiene este nodo y todos sus nodos hijos. |
| virtual [get_OwnerDocument](./get_ownerdocument/)() | Devuelve el [XmlDocument](../xmldocument/) al que pertenece este nodo. |
| virtual [get_ParentNode](./get_parentnode/)() | Devuelve el padre de este nodo (para nodos que pueden tener padres). |
| virtual [get_Prefix](./get_prefix/)() | Devuelve el prefijo de espacio de nombres de este nodo. |
| virtual [get_PreviousSibling](./get_previoussibling/)() | Devuelve el nodo que precede inmediatamente a este nodo. |
| virtual [get_PreviousText](./get_previoustext/)() | Devuelve el nodo de texto que precede inmediatamente a este nodo. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Devuelve el conjunto de información posterior a la validación del esquema que se ha asignado a este nodo como resultado de la validación del esquema. |
| virtual [get_Value](./get_value/)() | Devuelve el valor del nodo. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre los nodos hijos del nodo actual. |
| virtual [GetNamespaceOfPrefix](./getnamespaceofprefix/)(String) | Busca la declaración **xmlns** más cercana para el prefijo dado que está en el alcance del nodo actual y devuelve el URI del espacio de nombres en la declaración. |
| virtual [GetPrefixOfNamespace](./getprefixofnamespace/)(String) | Busca la declaración **xmlns** más cercana para el URI del espacio de nombres dado que está en el alcance del nodo actual y devuelve el prefijo definido en esa declaración. |
| virtual [idx_get](./idx_get/)(String) | Devuelve el primer elemento hijo con el [XmlNode::get_Name](./get_name/) especificado. |
| virtual [idx_get](./idx_get/)(String, String) | Devuelve el primer elemento hijo con los valores especificados de [XmlNode::get_LocalName](./get_localname/) y [XmlNode::get_NamespaceURI](./get_namespaceuri/). |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Inserta el nodo especificado inmediatamente después del nodo de referencia especificado. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado. |
| virtual [Normalize](./normalize/)() | Coloca todos los nodos [XmlText](../xmltext/) en toda la profundidad del subárbol bajo este [XmlNode](./) en una forma "normal" donde solo el marcado (es decir, etiquetas, comentarios, instrucciones de procesamiento, secciones CDATA y referencias de entidad) separa los nodos [XmlText](../xmltext/), es decir, no hay nodos [XmlText](../xmltext/) adyacentes. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) | Añade el nodo especificado al comienzo de la lista de nodos hijos de este nodo. |
| virtual [RemoveAll](./removeall/)() | Elimina todos los nodos hijos y/o atributos del nodo actual. |
| virtual [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) | Elimina el nodo hijo especificado. |
| virtual [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) | Reemplaza el nodo hijo **oldChild** con el nodo **newChild**. |
| [SelectNodes](./selectnodes/)(const String\&) | Selecciona una lista de nodos que coinciden con la expresión [XPath](../../system.xml.xpath/). |
| [SelectNodes](./selectnodes/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Selecciona una lista de nodos que coinciden con la expresión [XPath](../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../system.xml.xpath/) se resuelve usando el [XmlNamespaceManager](../xmlnamespacemanager/) suministrado. |
| [SelectSingleNode](./selectsinglenode/)(const String\&) | Selecciona el primer [XmlNode](./) que coincide con la expresión [XPath](../../system.xml.xpath/). |
| [SelectSingleNode](./selectsinglenode/)(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) | Selecciona el primer [XmlNode](./) que coincide con la expresión [XPath](../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../system.xml.xpath/) se resuelve usando el [XmlNamespaceManager](../xmlnamespacemanager/) suministrado. |
| virtual [set_InnerText](./set_innertext/)(String) | Establece los valores concatenados del nodo y de todos sus nodos hijos. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Establece el marcado que representa solo los nodos hijos de este nodo. |
| virtual [set_Prefix](./set_prefix/)(String) | Establece el prefijo de espacio de nombres de este nodo. |
| virtual [set_Value](./set_value/)(String) | Establece el valor del nodo. |
| virtual [Supports](./supports/)(String, String) | Comprueba si la implementación DOM implementa una característica específica. |
| virtual [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) | Guarda todos los nodos hijos del nodo en el [XmlWriter](../xmlwriter/) especificado, cuando se sobrescribe en una clase derivada. |
| virtual [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) | Guarda el nodo actual en el [XmlWriter](../xmlwriter/) especificado, cuando se sobrescribe en una clase derivada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
