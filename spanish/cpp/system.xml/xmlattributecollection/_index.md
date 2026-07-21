---
title: "System::Xml::XmlAttributeCollection clase"
linktitle: "XmlAttributeCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlAttributeCollection clase. Representa una colección de atributos que pueden ser accedidos por nombre o índice en C++."
type: docs
weight: 700
url: /es/cpp/system.xml/xmlattributecollection/
---
## XmlAttributeCollection class


Representa una colección de atributos que pueden accederse por nombre o índice.

```cpp
class XmlAttributeCollection : public System::Xml::XmlNamedNodeMap
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Append](./append/)(const SharedPtr\<XmlAttribute\>\&) | Inserta el atributo especificado como el último nodo en la colección. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&, int32_t) | Copia todos los objetos [XmlAttribute](../xmlattribute/) de esta colección al arreglo dado. |
| [idx_get](./idx_get/)(int32_t) | Devuelve el atributo con el índice especificado. |
| [idx_get](./idx_get/)(const String\&) | Devuelve el atributo con el nombre especificado. |
| [idx_get](./idx_get/)(const String\&, const String\&) | Devuelve el atributo con el nombre local y el URI (Identificador Uniforme de Recursos) del espacio de nombres especificados. |
| [InsertAfter](./insertafter/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Inserta el atributo especificado inmediatamente después del atributo de referencia especificado. |
| [InsertBefore](./insertbefore/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Inserta el atributo especificado inmediatamente antes del atributo de referencia especificado. |
| [Prepend](./prepend/)(const SharedPtr\<XmlAttribute\>\&) | Inserta el atributo especificado como el primer nodo en la colección. |
| [Remove](./remove/)(const SharedPtr\<XmlAttribute\>\&) | Elimina el atributo especificado de la colección. |
| [RemoveAll](./removeall/)() | Elimina todos los atributos de la colección. |
| [RemoveAt](./removeat/)(int32_t) | Elimina el atributo correspondiente al índice especificado de la colección. |
| [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) override | Agrega un [XmlNode](../xmlnode/) usando el resultado de su [XmlNode::get_Name](../xmlnode/get_name/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlNamedNodeMap](../xmlnamednodemap/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
