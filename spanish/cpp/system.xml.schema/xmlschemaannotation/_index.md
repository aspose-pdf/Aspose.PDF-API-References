---
title: "Clase System::Xml::Schema::XmlSchemaAnnotation"
linktitle: "XmlSchemaAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaAnnotation. Representa el elemento de anotación del World Wide Web Consortium (W3C) en C++."
type: docs
weight: 700
url: /es/cpp/system.xml.schema/xmlschemaannotation/
---
## XmlSchemaAnnotation class


Representa el elemento **annotation** del World Wide [Web](../../system.web/) Consortium (W3C).

```cpp
class XmlSchemaAnnotation : public System::Xml::Schema::XmlSchemaObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Id](./get_id/)() | Devuelve el identificador de cadena. |
| [get_Items](./get_items/)() | Devuelve la colección **Items** que se usa para almacenar los elementos secundarios **appinfo** y **documentation**. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Devuelve los atributos calificados que no pertenecen al espacio de nombres de destino del esquema. |
| [set_Id](./set_id/)(const String\&) | Establece el identificador de cadena. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Establece los atributos calificados que no pertenecen al espacio de nombres de destino del esquema. |
| [XmlSchemaAnnotation](./xmlschemaannotation/)() | Inicializa una nueva instancia de la clase [XmlSchemaAnnotation](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
