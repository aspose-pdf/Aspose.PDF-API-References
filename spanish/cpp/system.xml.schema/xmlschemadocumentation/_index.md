---
title: "System::Xml::Schema::XmlSchemaDocumentation clase"
linktitle: "XmlSchemaDocumentation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaDocumentation. Representa el elemento de documentación del XML Schema según lo especificado por el Consorcio World Wide Web (W3C). Esta clase especifica información que debe ser leída o utilizada por humanos dentro de una anotación en C++."
type: docs
weight: 2500
url: /es/cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


Representa el elemento **documentation** del XML [Schema](../) según lo especificado por el Consorcio World Wide [Web](../../system.web/) (W3C). Esta clase especifica información que debe ser leída o utilizada por humanos dentro de una **annotation**.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Language](./get_language/)() | Devuelve el atributo **xml:lang**. Esto sirve como indicador del idioma utilizado en el contenido. |
| [get_Markup](./get_markup/)() | Devuelve una matriz de objetos [XmlNode](../../system.xml/xmlnode/) que representan los nodos hijos de documentación. |
| [get_Source](./get_source/)() | Devuelve la fuente del Identificador Uniforme de Recursos (URI) de la información. |
| [set_Language](./set_language/)(const String\&) | Establece el atributo **xml:lang**. Esto sirve como indicador del idioma utilizado en el contenido. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Establece una matriz de objetos [XmlNode](../../system.xml/xmlnode/) que representan los nodos hijos de documentación. |
| [set_Source](./set_source/)(const String\&) | Establece la fuente del Identificador Uniforme de Recursos (URI) de la información. |
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
