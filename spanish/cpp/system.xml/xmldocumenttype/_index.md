---
title: "Clase System::Xml::XmlDocumentType"
linktitle: "XmlDocumentType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlDocumentType. Representa la declaración de tipo de documento en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml/xmldocumenttype/
---
## XmlDocumentType class


Representa la declaración del tipo de documento.

```cpp
class XmlDocumentType : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [get_Entities](./get_entities/)() | Devuelve la colección de nodos [XmlEntity](../xmlentity/) declarados en la declaración del tipo de documento. |
| [get_InternalSubset](./get_internalsubset/)() | Devuelve el valor del subconjunto interno de la definición del tipo de documento (DTD) en la declaración DOCTYPE. |
| [get_IsReadOnly](./get_isreadonly/)() override | Devuelve un valor que indica si el nodo es de solo lectura. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Notations](./get_notations/)() | Devuelve la colección de nodos [XmlNotation](../xmlnotation/) presentes en la declaración del tipo de documento. |
| [get_PublicId](./get_publicid/)() | Devuelve el valor del identificador público en la declaración DOCTYPE. |
| [get_SystemId](./get_systemid/)() | Devuelve el valor del identificador del sistema en la declaración DOCTYPE. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo en el [XmlWriter](../xmlwriter/) especificado. Para nodos [XmlDocumentType](./), este método no tiene efecto. |
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
