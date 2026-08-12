---
title: "System::Xml::XmlText class"
linktitle: "XmlText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlText class. Representa el contenido de texto de un elemento o atributo en C++."
type: docs
weight: 3800
url: /es/cpp/system.xml/xmltext/
---
## XmlText class


Representa el contenido de texto de un elemento o atributo.

```cpp
class XmlText : public System::Xml::XmlCharacterData
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_PreviousText](./get_previoustext/)() override | Devuelve el nodo de texto que precede inmediatamente a este nodo. |
| [get_Value](./get_value/)() override | Devuelve el valor del nodo. |
| [set_Value](./set_value/)(String) override | Establece el valor del nodo. |
| virtual [SplitText](./splittext/)(int32_t) | Divide el nodo en dos nodos en el desplazamiento especificado, manteniéndolos ambos en el árbol como hermanos. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. Los nodos [XmlText](./) no tienen hijos, por lo que este método no tiene efecto. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo en el [XmlWriter](../xmlwriter/) especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
