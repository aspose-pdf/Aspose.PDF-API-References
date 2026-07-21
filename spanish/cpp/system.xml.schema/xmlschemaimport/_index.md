---
title: "Clase System::Xml::Schema::XmlSchemaImport"
linktitle: "XmlSchemaImport"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaImport. Representa el elemento import del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase se utiliza para importar componentes de esquema de otros esquemas en C++."
type: docs
weight: 3500
url: /es/cpp/system.xml.schema/xmlschemaimport/
---
## XmlSchemaImport class


Representa el elemento **import** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase se utiliza para importar componentes de esquema de otros esquemas.

```cpp
class XmlSchemaImport : public System::Xml::Schema::XmlSchemaExternal
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Annotation](./get_annotation/)() | Devuelve el valor **annotation**. |
| [get_Namespace](./get_namespace/)() | Devuelve el espacio de nombres de destino para el esquema importado como una referencia Uniform Resource Identifier (URI). |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | Establece el valor **annotation**. |
| [set_Namespace](./set_namespace/)(const String\&) | Establece el espacio de nombres de destino para el esquema importado como una referencia Uniform Resource Identifier (URI). |
| [XmlSchemaImport](./xmlschemaimport/)() | Inicializa una nueva instancia de la clase [XmlSchemaImport](./). |
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
