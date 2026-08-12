---
title: "System::Xml::XmlElement clase"
linktitle: "XmlElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlElement clase. Representa un elemento en C++."
type: docs
weight: 1700
url: /es/cpp/system.xml/xmlelement/
---
## XmlElement class


Representa un elemento.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Devuelve un valor **bool** que indica si el nodo actual tiene algún atributo. |
| [get_InnerText](./get_innertext/)() override | Devuelve los valores concatenados del nodo y de todos sus hijos. |
| [get_InnerXml](./get_innerxml/)() override | Devuelve el marcado que representa solo los hijos de este nodo. |
| [get_IsEmpty](./get_isempty/)() | Devuelve el formato de etiqueta del elemento. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo actual. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve el URI del espacio de nombres de este nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Devuelve el [XmlDocument](../xmldocument/) al que pertenece este nodo. |
| [get_Prefix](./get_prefix/)() override | Devuelve el prefijo de espacio de nombres de este nodo. |
| [get_SchemaInfo](./get_schemainfo/)() override | Devuelve el conjunto de información posterior a la validación del esquema que se ha asignado a este nodo como resultado de la validación del esquema. |
| virtual [GetAttribute](./getattribute/)(String) | Devuelve el valor del atributo con el nombre especificado. |
| virtual [GetAttribute](./getattribute/)(String, String) | Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados. |
| virtual [GetAttributeNode](./getattributenode/)(String) | Devuelve el [XmlAttribute](../xmlattribute/) con el nombre especificado. |
| virtual [GetAttributeNode](./getattributenode/)(String, String) | Devuelve el [XmlAttribute](../xmlattribute/) con el nombre local y el URI del espacio de nombres especificados. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Devuelve una [XmlNodeList](../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlElement::get_Name](./get_name/) especificado. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Devuelve una [XmlNodeList](../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con los valores especificados de [XmlElement::get_LocalName](./get_localname/) y [XmlElement::get_NamespaceURI](./get_namespaceuri/). |
| virtual [HasAttribute](./hasattribute/)(String) | Determina si el nodo actual tiene un atributo con el nombre especificado. |
| virtual [HasAttribute](./hasattribute/)(String, String) | Determina si el nodo actual tiene un atributo con el nombre local y el URI del espacio de nombres especificados. |
| [RemoveAll](./removeall/)() override | Elimina todos los atributos y elementos secundarios especificados del nodo actual. Los atributos predeterminados no se eliminan. |
| virtual [RemoveAllAttributes](./removeallattributes/)() | Elimina todos los atributos especificados del elemento. Los atributos predeterminados no se eliminan. |
| virtual [RemoveAttribute](./removeattribute/)(String) | Elimina un atributo por nombre. |
| virtual [RemoveAttribute](./removeattribute/)(String, String) | Elimina un atributo con el nombre local y el URI del espacio de nombres especificados. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente). |
| virtual [RemoveAttributeAt](./removeattributeat/)(int32_t) | Elimina el nodo de atributo con el índice especificado del elemento. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente). |
| virtual [RemoveAttributeNode](./removeattributenode/)(SharedPtr\<XmlAttribute\>) | Elimina el [XmlAttribute](../xmlattribute/) especificado. |
| virtual [RemoveAttributeNode](./removeattributenode/)(String, String) | Elimina el [XmlAttribute](../xmlattribute/) especificado por el nombre local y el URI del espacio de nombres. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente). |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados del nodo y todos sus hijos. |
| [set_InnerXml](./set_innerxml/)(String) override | Establece el marcado que representa solo los hijos de este nodo. |
| [set_IsEmpty](./set_isempty/)(bool) | Establece el formato de etiqueta del elemento. |
| [set_Prefix](./set_prefix/)(String) override | Establece el prefijo de espacio de nombres de este nodo. |
| virtual [SetAttribute](./setattribute/)(String, String) | Establece el valor del atributo con el nombre especificado. |
| virtual [SetAttribute](./setattribute/)(String, String, String) | Establece el valor del atributo con el nombre local y el URI del espacio de nombres especificados. |
| virtual [SetAttributeNode](./setattributenode/)(SharedPtr\<XmlAttribute\>) | Agrega el [XmlAttribute](../xmlattribute/) especificado. |
| virtual [SetAttributeNode](./setattributenode/)(String, String) | Agrega el [XmlAttribute](../xmlattribute/) especificado. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo actual en el [XmlWriter](../xmlwriter/) especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
