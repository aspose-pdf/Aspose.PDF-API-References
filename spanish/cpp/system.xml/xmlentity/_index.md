---
title: "Clase System::Xml::XmlEntity"
linktitle: "XmlEntity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlEntity. Representa una declaración de entidad, como <!ENTITY... > en C++."
type: docs
weight: 1800
url: /es/cpp/system.xml/xmlentity/
---
## XmlEntity class


Representa una declaración de entidad, como **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. Los nodos de entidad no pueden clonarse. Llamar a este método en un objeto [XmlEntity](./) lanza una excepción. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve el Identificador Uniforme de Recursos (URI) base del nodo actual. |
| [get_InnerText](./get_innertext/)() override | Devuelve los valores concatenados del nodo de entidad y todos sus hijos. |
| [get_InnerXml](./get_innerxml/)() override | Devuelve el marcado que representa los hijos de este nodo. |
| [get_IsReadOnly](./get_isreadonly/)() override | Devuelve un valor que indica si el nodo es de solo lectura. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre del nodo sin el prefijo del espacio de nombres. |
| [get_Name](./get_name/)() override | Devuelve el nombre del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo. |
| [get_NotationName](./get_notationname/)() | Devuelve el nombre del atributo NDATA opcional en la declaración de entidad. |
| [get_OuterXml](./get_outerxml/)() override | Devuelve el marcado que representa este nodo y todos sus hijos. |
| [get_PublicId](./get_publicid/)() | Devuelve el valor del identificador público en la declaración de entidad. |
| [get_SystemId](./get_systemid/)() | Devuelve el valor del identificador del sistema en la declaración de entidad. |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados del nodo de entidad y todos sus hijos. |
| [set_InnerXml](./set_innerxml/)(String) override | Establece el marcado que representa los hijos de este nodo. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. Para los nodos [XmlEntity](./), este método no tiene efecto. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo en el [XmlWriter](../xmlwriter/) especificado. Para los nodos [XmlEntity](./), este método no tiene efecto. |
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
