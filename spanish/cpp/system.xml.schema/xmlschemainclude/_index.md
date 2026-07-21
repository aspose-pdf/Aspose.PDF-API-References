---
title: "System::Xml::Schema::XmlSchemaInclude class"
linktitle: "XmlSchemaInclude"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaInclude class. Representa el elemento include de XML Schema según lo especificado por el Consorcio de la World Wide Web (W3C). Esta clase se usa para incluir declaraciones y definiciones de un esquema externo. Las declaraciones y definiciones incluidas están entonces disponibles para su procesamiento en el esquema contenedor en C++."
type: docs
weight: 3600
url: /es/cpp/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude class


Representa el elemento **include** de XML [Schema](../) según lo especificado por el Consorcio de la World Wide [Web](../../system.web/) (W3C). Esta clase se usa para incluir declaraciones y definiciones de un esquema externo. Las declaraciones y definiciones incluidas están entonces disponibles para su procesamiento en el esquema contenedor.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Devuelve el valor **annotation**. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Establece el valor **annotation**. |
| [XmlSchemaInclude](./xmlschemainclude/)() | Inicializa una nueva instancia de la clase [XmlSchemaInclude](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
