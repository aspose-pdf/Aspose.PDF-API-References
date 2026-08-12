---
title: "Clase System::Xml::XmlDocumentFragment"
linktitle: "XmlDocumentFragment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlDocumentFragment. Representa un objeto ligero que es útil para operaciones de inserción de árbol en C++."
type: docs
weight: 1500
url: /es/cpp/system.xml/xmldocumentfragment/
---
## XmlDocumentFragment class


Representa un objeto ligero que es útil para operaciones de inserción en árboles.

```cpp
class XmlDocumentFragment : public System::Xml::XmlNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_InnerXml](./get_innerxml/)() override | Devuelve el marcado que representa los hijos de este nodo. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Devuelve el [XmlDocument](../xmldocument/) al que pertenece este nodo. |
| [set_InnerXml](./set_innerxml/)(String) override | Establece el marcado que representa los hijos de este nodo. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo en el [XmlWriter](../xmlwriter/) especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
