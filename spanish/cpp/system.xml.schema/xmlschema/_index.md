---
title: "Clase System::Xml::Schema::XmlSchema"
linktitle: "XmlSchema"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchema. Una representación en memoria de un esquema XML, según lo especificado por el Consorcio de la World Wide Web (W3C) y en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.schema/xmlschema/
---
## XmlSchema class


Una representación en memoria de un [Schema](../) XML, según lo especificado por el Consorcio de la World Wide [Web](../../system.web/) (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) y [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Compile](./compile/)(ValidationEventHandler) | Compila el modelo [Schema](../)[Object](../../system/object/) (SOM) de XML en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La comprobación de validación semántica se realiza durante la compilación. |
| [Compile](./compile/)(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) | Compila el modelo [Schema](../)[Object](../../system/object/) (SOM) de XML en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La comprobación de validación semántica se realiza durante la compilación. |
| [get_AttributeFormDefault](./get_attributeformdefault/)() | Devuelve la forma de los atributos declarados en el espacio de nombres de destino del esquema. |
| [get_AttributeGroups](./get_attributegroups/)() | Devuelve el valor posterior a la compilación del esquema de todos los grupos de atributos globales en el esquema. |
| [get_Attributes](./get_attributes/)() | Devuelve el valor posterior a la compilación del esquema para todos los atributos en el esquema. |
| [get_BlockDefault](./get_blockdefault/)() | Devuelve el atributo **blockDefault** que establece el valor predeterminado del atributo **block** en elementos y tipos complejos en el **targetNamespace** del esquema. |
| [get_ElementFormDefault](./get_elementformdefault/)() | Devuelve la forma de los elementos declarados en el espacio de nombres de destino del esquema. |
| [get_Elements](./get_elements/)() | Devuelve el valor posterior a la compilación del esquema para todos los elementos en el esquema. |
| [get_FinalDefault](./get_finaldefault/)() | Devuelve el atributo **finalDefault** que establece el valor predeterminado del atributo **final** en elementos y tipos complejos en el espacio de nombres de destino del esquema. |
| [get_Groups](./get_groups/)() | Devuelve el valor posterior a la compilación del esquema de todos los grupos en el esquema. |
| [get_Id](./get_id/)() | Devuelve el ID de cadena. |
| [get_Includes](./get_includes/)() | Devuelve la colección de esquemas incluidos e importados. |
| [get_IsCompiled](./get_iscompiled/)() | Indica si el esquema ha sido compilado. |
| [get_Items](./get_items/)() | Devuelve la colección de elementos del esquema en el esquema y se utiliza para agregar nuevos tipos de elemento a nivel del elemento **schema**. |
| [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Devuelve el número de línea en el archivo al que se refiere el elemento **schema**. |
| [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Devuelve la posición de línea en el archivo al que se refiere el elemento **schema**. |
| [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Devuelve los XmlSerializerNamespaces para usar con este objeto de esquema. |
| [get_Notations](./get_notations/)() | Devuelve el valor posterior a la compilación del esquema para todas las notaciones en el esquema. |
| [get_Parent](../xmlschemaobject/get_parent/)() | Devuelve el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| [get_SchemaTypes](./get_schematypes/)() | Devuelve el valor posterior a la compilación del esquema de todos los tipos de esquema en el esquema. |
| [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Devuelve la ubicación de origen del archivo que cargó el esquema. |
| [get_TargetNamespace](./get_targetnamespace/)() | Devuelve el Identificador Uniforme de Recursos (URI) del espacio de nombres de destino del esquema. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Devuelve los atributos calificados que no pertenecen al espacio de nombres de destino del esquema. |
| [get_Version](./get_version/)() | Devuelve la versión del esquema. |
| static [Read](./read/)(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) | Lee un XML [Schema](../) del [IO::TextReader](../../system.io/textreader/) suministrado. |
| static [Read](./read/)(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) | Lee un XML [Schema](../) del flujo suministrado. |
| static [Read](./read/)(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) | Lee un XML [Schema](../) del [XmlReader](../../system.xml/xmlreader/) suministrado. |
| [set_AttributeFormDefault](./set_attributeformdefault/)(XmlSchemaForm) | Establece la forma de los atributos declarados en el espacio de nombres de destino del esquema. |
| [set_BlockDefault](./set_blockdefault/)(XmlSchemaDerivationMethod) | Establece el atributo **blockDefault**, que define el valor predeterminado del atributo **block** en elementos y tipos complejos en el **targetNamespace** del esquema. |
| [set_ElementFormDefault](./set_elementformdefault/)(XmlSchemaForm) | Establece la forma de los elementos declarados en el espacio de nombres de destino del esquema. |
| [set_FinalDefault](./set_finaldefault/)(XmlSchemaDerivationMethod) | Establece el atributo **finalDefault**, que define el valor predeterminado del atributo **final** en elementos y tipos complejos en el espacio de nombres de destino del esquema. |
| [set_Id](./set_id/)(const String\&) | Establece el ID de cadena. |
| [set_LineNumber](../xmlschemaobject/set_linenumber/)(int32_t) | Establece el número de línea en el archivo al que se refiere el elemento **schema**. |
| [set_LinePosition](../xmlschemaobject/set_lineposition/)(int32_t) | Establece la posición de línea en el archivo al que se refiere el elemento **schema**. |
| [set_Namespaces](../xmlschemaobject/set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Establece los XmlSerializerNamespaces a usar con este objeto de esquema. |
| [set_Parent](../xmlschemaobject/set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Establece el padre de este [XmlSchemaObject](../xmlschemaobject/). |
| [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const String\&) | Establece la ubicación de origen del archivo que cargó el esquema. |
| [set_TargetNamespace](./set_targetnamespace/)(const String\&) | Establece el Identificador Uniforme de Recursos (URI) del espacio de nombres de destino del esquema. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Establece los atributos calificados que no pertenecen al espacio de nombres de destino del esquema. |
| [set_Version](./set_version/)(const String\&) | Establece la versión del esquema. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&) | Escribe el XML [Schema](../) en el flujo de datos suministrado. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Escribe el XML [Schema](../) en el Stream suministrado usando el [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) especificado. |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&) | Escribe el XML [Schema](../) en el [IO::TextWriter](../../system.io/textwriter/) suministrado. |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Escribe el XML [Schema](../) en el TextWriter suministrado. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&) | Escribe el XML [Schema](../) al [XmlWriter](../../system.xml/xmlwriter/) suministrado. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Escribe el XML [Schema](../) al [XmlWriter](../../system.xml/xmlwriter/) suministrado. |
| [XmlSchema](./xmlschema/)() | Inicializa una nueva instancia de la clase [XmlSchema](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializa una nueva instancia de la clase [XmlSchemaObject](../xmlschemaobject/). |
## Campos

| Campo | Descripción |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | El espacio de nombres de instancia del esquema XML. Este campo es constante. |
| static [Namespace](./namespace/) | El espacio de nombres del esquema XML. Este campo es constante. |
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
