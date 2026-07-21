---
title: "System::Xml::Schema::XmlSchemaValidator clase"
linktitle: "XmlSchemaValidator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaValidator clase. Representa un motor de validación de esquemas de Lenguaje de Definición de Esquemas XML (XSD). La clase XmlSchemaValidator no puede heredarse en C++."
type: docs
weight: 7000
url: /es/cpp/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator class


Representa un motor de validación de [Schema](../) de Lenguaje de Definición XML (XSD) [Schema](../). La clase [XmlSchemaValidator](./) no puede heredarse.

```cpp
class XmlSchemaValidator : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddSchema](./addschema/)(const SharedPtr\<XmlSchema\>\&) | Agrega un [Schema](../) de Lenguaje de Definición XML (XSD) al conjunto de esquemas utilizados para la validación. |
| [EndValidation](./endvalidation/)() | Finaliza la validación y verifica las restricciones de identidad para todo el documento XML. |
| [get_LineInfoProvider](./get_lineinfoprovider/)() | Devuelve la información del número de línea del nodo XML que se está validando. |
| [get_SourceUri](./get_sourceuri/)() | Devuelve el URI de origen del nodo XML que se está validando. |
| [get_ValidationEventSender](./get_validationeventsender/)() | Devuelve el objeto enviado como el objeto remitente de un evento de validación. |
| [GetExpectedAttributes](./getexpectedattributes/)() | Devuelve los atributos esperados para el contexto del elemento actual. |
| [GetExpectedParticles](./getexpectedparticles/)() | Devuelve las partículas esperadas en el contexto del elemento actual. |
| [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) | Valida las restricciones de identidad en los atributos predeterminados y rellena la List especificada con objetos [XmlSchemaAttribute](../xmlschemaattribute/) para cualquier atributo con valores predeterminados que no haya sido validado previamente usando el método [XmlSchemaValidator::ValidateAttribute](./validateattribute/) en el contexto del elemento. |
| [Initialize](./initialize/)() | Inicializa el estado del objeto [XmlSchemaValidator](./). |
| [Initialize](./initialize/)(const SharedPtr\<XmlSchemaObject\>\&) | Inicializa el estado del objeto [XmlSchemaValidator](./) usando el [XmlSchemaObject](../xmlschemaobject/) especificado para validación parcial. |
| [set_LineInfoProvider](./set_lineinfoprovider/)(const SharedPtr\<IXmlLineInfo\>\&) | Establece la información del número de línea para el nodo XML que se está validando. |
| [set_SourceUri](./set_sourceuri/)(const SharedPtr\<Uri\>\&) | Establece el URI de origen para el nodo XML que se está validando. |
| [set_ValidationEventSender](./set_validationeventsender/)(const SharedPtr\<Object\>\&) | Establece el objeto enviado como el objeto remitente de un evento de validación. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el objeto [XmlResolver](../../system.xml/xmlresolver/) utilizado para resolver los elementos **xs:import** y **xs:include**, así como los atributos **xsi:schemaLocation** y **xsi:noNamespaceSchemaLocation**. |
| [SkipToEndElement](./skiptoendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Omite la validación del contenido del elemento actual y prepara el objeto [XmlSchemaValidator](./) para validar contenido en el contexto del elemento padre. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) | Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Valida el elemento en el contexto actual. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) | Valida el elemento en el contexto actual con los valores de los atributos **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** y **xsi:NoNamespaceSchemaLocation** especificados. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifica si el contenido de texto del elemento es válido según su tipo de datos para elementos con contenido simple, y verifica si el contenido del elemento actual está completo para elementos con contenido complejo. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) | Verifica si el contenido de texto del elemento especificado es válido según su tipo de datos. |
| [ValidateEndOfAttributes](./validateendofattributes/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifica si todos los atributos requeridos en el contexto del elemento están presentes y prepara el objeto [XmlSchemaValidator](./) para validar el contenido hijo del elemento. |
| [ValidateText](./validatetext/)(const String\&) | Valida si la **string** de texto especificada está permitida en el contexto del elemento actual, y acumula el texto para la validación si el elemento actual tiene contenido simple. |
| [ValidateText](./validatetext/)(XmlValueGetter) | Valida si el texto devuelto por el objeto [XmlValueGetter](../xmlvaluegetter/) especificado está permitido en el contexto del elemento actual, y acumula el texto para la validación si el elemento actual tiene contenido simple. |
| [ValidateWhitespace](./validatewhitespace/)(const String\&) | Valida si el espacio en blanco en la **string** especificada está permitido en el contexto del elemento actual, y acumula el espacio en blanco para la validación si el elemento actual tiene contenido simple. |
| [ValidateWhitespace](./validatewhitespace/)(XmlValueGetter) | Valida si el espacio en blanco devuelto por el objeto [XmlValueGetter](../xmlvaluegetter/) especificado está permitido en el contexto del elemento actual, y acumula el espacio en blanco para la validación si el elemento actual tiene contenido simple. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) | Inicializa una nueva instancia de la clase [XmlSchemaValidator](./). |
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
