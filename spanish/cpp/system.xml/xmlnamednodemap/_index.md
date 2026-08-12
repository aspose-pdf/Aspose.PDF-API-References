---
title: "System::Xml::XmlNamedNodeMap clase"
linktitle: "XmlNamedNodeMap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlNamedNodeMap clase. Representa una colección de nodos que pueden ser accedidos por nombre o índice en C++."
type: docs
weight: 2200
url: /es/cpp/system.xml/xmlnamednodemap/
---
## XmlNamedNodeMap class


Representa una colección de nodos que pueden accederse por nombre o índice.

```cpp
class XmlNamedNodeMap : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [begin](./begin/)() const | Obtiene el iterador al primer elemento de la colección. |
| [cbegin](./cbegin/)() const | Obtiene el iterador al primer elemento de la colección. |
| [cend](./cend/)() const | Obtiene el iterador para un elemento inexistente detrás del último elemento de la colección. |
| [end](./end/)() const | Obtiene el iterador para un elemento inexistente detrás del último elemento de la colección. |
| virtual [get_Count](./get_count/)() | Devuelve el número de nodos en el [XmlNamedNodeMap](./). |
| [GetEnumerator](./getenumerator/)() override | Proporciona soporte para la iteración sobre la colección de nodos en el [XmlNamedNodeMap](./). |
| virtual [GetNamedItem](./getnameditem/)(String) | Recupera un [XmlNode](../xmlnode/) especificado por nombre. |
| virtual [GetNamedItem](./getnameditem/)(String, String) | Recupera un nodo con los valores coincidentes de [XmlNode::get_LocalName](../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [Item](./item/)(int32_t) | Recupera el nodo en el índice especificado en el [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String) | Elimina el nodo del [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String, String) | Elimina un nodo con los valores coincidentes de [XmlNode::get_LocalName](../xmlnode/get_localname/) y [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) | Agrega un [XmlNode](../xmlnode/) usando su valor [XmlNode::get_Name](../xmlnode/get_name/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [iterator](./iterator/) | Tipo de iterador. |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
