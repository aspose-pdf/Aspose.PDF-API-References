---
title: "System::Xml::Schema::XmlSchemaObject class"
linktitle: "XmlSchemaObject"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaObject class. Representa la clase raíz para la jerarquía del modelo de objetos del esquema Xml y sirve como clase base para clases como la clase XmlSchema en C++."
type: docs
weight: 5000
url: /es/cpp/system.xml.schema/xmlschemaobject/
---
## XmlSchemaObject class


Representa la clase raíz para la jerarquía del modelo de objetos del esquema [Xml](../../system.xml/) y sirve como clase base para clases como la clase [XmlSchema](../xmlschema/).

```cpp
class XmlSchemaObject : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_LineNumber](./get_linenumber/)() | Devuelve el número de línea en el archivo al que se refiere el elemento **schema**. |
| [get_LinePosition](./get_lineposition/)() | Devuelve la posición de línea en el archivo al que se refiere el elemento **schema**. |
| [get_Namespaces](./get_namespaces/)() | Devuelve los XmlSerializerNamespaces para usar con este objeto de esquema. |
| [get_Parent](./get_parent/)() | Devuelve el padre de este [XmlSchemaObject](./). |
| [get_SourceUri](./get_sourceuri/)() | Devuelve la ubicación de origen del archivo que cargó el esquema. |
| [set_LineNumber](./set_linenumber/)(int32_t) | Establece el número de línea en el archivo al que se refiere el elemento **schema**. |
| [set_LinePosition](./set_lineposition/)(int32_t) | Establece la posición de línea en el archivo al que se refiere el elemento **schema**. |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Establece los XmlSerializerNamespaces a usar con este objeto de esquema. |
| [set_Parent](./set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Establece el padre de este [XmlSchemaObject](./). |
| [set_SourceUri](./set_sourceuri/)(const String\&) | Establece la ubicación de origen del archivo que cargó el esquema. |
| [XmlSchemaObject](./xmlschemaobject/)() | Inicializa una nueva instancia de la clase [XmlSchemaObject](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
