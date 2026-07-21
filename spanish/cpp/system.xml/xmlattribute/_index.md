---
title: "Clase System::Xml::XmlAttribute"
linktitle: "XmlAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlAttribute. Representa un atributo. Los valores válidos y predeterminados para el atributo se definen en una definición de tipo de documento (DTD) o esquema en C++."
type: docs
weight: 600
url: /es/cpp/system.xml/xmlattribute/
---
## XmlAttribute class


Representa un atributo. Los valores válidos y predeterminados del atributo se definen en una definición de tipo de documento (DTD) o esquema.

```cpp
class XmlAttribute : public System::Xml::XmlNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) override | Agrega el nodo especificado al final de la lista de nodos hijos de este nodo. |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve el Identificador Uniforme de Recursos (URI) base del nodo. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve el URI del espacio de nombres de este nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Devuelve el [XmlDocument](../xmldocument/) al que pertenece este nodo. |
| virtual [get_OwnerElement](./get_ownerelement/)() | Devuelve el [XmlElement](../xmlelement/) al que pertenece el atributo. |
| [get_Prefix](./get_prefix/)() override | Devuelve el prefijo de espacio de nombres de este nodo. |
| [get_SchemaInfo](./get_schemainfo/)() override | Devuelve el post-schema-validation-infoset que se ha asignado a este nodo como resultado de la validación del esquema. |
| virtual [get_Specified](./get_specified/)() | Devuelve un valor que indica si el valor del atributo se estableció explícitamente. |
| [get_Value](./get_value/)() override | Devuelve el valor del nodo. |
| [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Inserta el nodo especificado inmediatamente después del nodo de referencia especificado. |
| [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Inserta el nodo especificado inmediatamente antes del nodo de referencia especificado. |
| [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) override | Añade el nodo especificado al comienzo de la lista de nodos hijos de este nodo. |
| [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) override | Elimina el nodo hijo especificado. |
| [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Reemplaza el nodo hijo especificado con el nuevo nodo hijo especificado. |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados del nodo y todos sus hijos. |
| [set_InnerXml](./set_innerxml/)(String) override | Establece el valor del atributo. |
| [set_Prefix](./set_prefix/)(String) override | Establece el prefijo de espacio de nombres de este nodo. |
| [set_Value](./set_value/)(String) override | Establece el valor del nodo. |
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
