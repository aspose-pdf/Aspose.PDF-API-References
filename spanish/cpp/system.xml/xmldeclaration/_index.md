---
title: "Clase System::Xml::XmlDeclaration"
linktitle: "XmlDeclaration"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlDeclaration. Representa el nodo de declaración XML <?xml version=''1.0''...?> en C++."
type: docs
weight: 1300
url: /es/cpp/system.xml/xmldeclaration/
---
## XmlDeclaration class


Representa el nodo de declaración XML **<?xml version='1.0'...?>**.

```cpp
class XmlDeclaration : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_Encoding](./get_encoding/)() | Devuelve el nivel de codificación del documento XML. |
| [get_InnerText](./get_innertext/)() override | Devuelve los valores concatenados de la [XmlDeclaration](./). |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Standalone](./get_standalone/)() | Devuelve el valor del atributo standalone. |
| [get_Value](./get_value/)() override | Devuelve el valor de la [XmlDeclaration](./). |
| [get_Version](./get_version/)() | Devuelve la versión XML del documento. |
| [set_Encoding](./set_encoding/)(const String\&) | Establece el nivel de codificación del documento XML. |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados de la [XmlDeclaration](./). |
| [set_Standalone](./set_standalone/)(const String\&) | Establece el valor del atributo standalone. |
| [set_Value](./set_value/)(String) override | Establece el valor de la [XmlDeclaration](./). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. Debido a que los nodos [XmlDeclaration](./) no tienen hijos, este método no tiene efecto. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo en el [XmlWriter](../xmlwriter/) especificado. |
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
