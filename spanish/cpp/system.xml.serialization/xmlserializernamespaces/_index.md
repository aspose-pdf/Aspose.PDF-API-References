---
title: "System::Xml::Serialization::XmlSerializerNamespaces clase"
linktitle: "XmlSerializerNamespaces"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Serialization::XmlSerializerNamespaces clase. Contiene los espacios de nombres XML y los prefijos que el Serialization::XmlSerializer utiliza para generar nombres calificados en una instancia de documento XML en C++."
type: docs
weight: 800
url: /es/cpp/system.xml.serialization/xmlserializernamespaces/
---
## XmlSerializerNamespaces class


Contiene los espacios de nombres XML y los prefijos que el [Serialization::XmlSerializer](../xmlserializer/) utiliza para generar nombres calificados en una instancia de documento XML.

```cpp
class XmlSerializerNamespaces : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Agrega un par de prefijo y espacio de nombres a un objeto [Serialization::XmlSerializerNamespaces](./). |
| [get_Count](./get_count/)() | Devuelve el número de pares de prefijo y espacio de nombres en la colección. |
| [get_NamespaceList](./get_namespacelist/)() |  |
| [get_Namespaces](./get_namespaces/)() |  |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<Collections::Generic::Dictionary\<String, String\>\>\&) |  |
| [ToArray](./toarray/)() | Devuelve la matriz de pares de prefijo y espacio de nombres en un objeto [Serialization::XmlSerializerNamespaces](./). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)() | Inicializa una nueva instancia de la clase [Serialization::XmlSerializerNamespaces](./). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const SharedPtr\<XmlSerializerNamespaces\>\&) | Inicializa una nueva instancia de la clase [Serialization::XmlSerializerNamespaces](./), usando la instancia especificada de **[XmlSerializerNamespaces](./)** que contiene la colección de pares de prefijo y espacio de nombres. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Inicializa una nueva instancia de la clase [Serialization::XmlSerializerNamespaces](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
