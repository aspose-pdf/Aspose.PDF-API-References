---
title: "Clase System::Xml::XmlProcessingInstruction"
linktitle: "XmlProcessingInstruction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlProcessingInstruction. Representa una instrucción de procesamiento, que XML define para mantener información específica del procesador en el texto del documento en C++."
type: docs
weight: 3100
url: /es/cpp/system.xml/xmlprocessinginstruction/
---
## XmlProcessingInstruction class


Representa una instrucción de procesamiento, que XML define para mantener información específica del procesador en el texto del documento.

```cpp
class XmlProcessingInstruction : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_Data](./get_data/)() | Devuelve el contenido de la instrucción de procesamiento, excluyendo el objetivo. |
| [get_InnerText](./get_innertext/)() override | Devuelve los valores concatenados del nodo y de todos sus hijos. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Target](./get_target/)() | Devuelve el objetivo de la instrucción de procesamiento. |
| [get_Value](./get_value/)() override | Devuelve el valor del nodo. |
| [set_Data](./set_data/)(const String\&) | Establece el contenido de la instrucción de procesamiento, excluyendo el objetivo. |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados del nodo y todos sus hijos. |
| [set_Value](./set_value/)(String) override | Establece el valor del nodo. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. Debido a que los nodos ProcessingInstruction no tienen hijos, este método no tiene efecto. |
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
