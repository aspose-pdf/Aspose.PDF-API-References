---
title: "Clase System::Xml::XmlReaderSettings"
linktitle: "XmlReaderSettings"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlReaderSettings. Especifica un conjunto de características para admitir en el objeto XmlReader creado por el método XmlReader::Create en C++."
type: docs
weight: 3400
url: /es/cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


Especifica un conjunto de características para admitir en el objeto [XmlReader](../xmlreader/) creado por el método [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CheckReadOnly](./checkreadonly/)(const String\&) |  |
| [Clone](./clone/)() | Crea una copia de la instancia de [XmlReaderSettings](./). |
| [get_CheckCharacters](./get_checkcharacters/)() | Devuelve un valor que indica si se debe realizar la comprobación de caracteres. |
| [get_CloseInput](./get_closeinput/)() | Devuelve un valor que indica si el flujo subyacente o TextReader debe cerrarse cuando se cierra el lector. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Devuelve el nivel de conformidad al que se ajustará el [XmlReader](../xmlreader/). |
| [get_DtdProcessing](./get_dtdprocessing/)() | Devuelve un valor que determina el procesamiento de los DTD. |
| [get_IgnoreComments](./get_ignorecomments/)() | Devuelve un valor que indica si se deben ignorar los comentarios. |
| [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Devuelve un valor que indica si se deben ignorar las instrucciones de procesamiento. |
| [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Devuelve un valor que indica si se debe ignorar el espacio en blanco insignificante. |
| [get_LineNumberOffset](./get_linenumberoffset/)() | Devuelve el desplazamiento del número de línea del objeto [XmlReader](../xmlreader/). |
| [get_LinePositionOffset](./get_linepositionoffset/)() | Devuelve el desplazamiento de la posición de línea del objeto [XmlReader](../xmlreader/). |
| [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Devuelve un valor que indica el número máximo permitido de caracteres en un documento que resultan de la expansión de entidades. |
| [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Devuelve un valor que indica el número máximo permitido de caracteres en un documento XML. Un valor cero (0) significa que no hay límites en el tamaño del documento XML. Un valor distinto de cero especifica el tamaño máximo, en caracteres. |
| [get_NameTable](./get_nametable/)() | Devuelve el [XmlNameTable](../xmlnametable/) utilizado para comparaciones de cadenas atomizadas. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Devuelve un valor que indica si se debe prohibir el procesamiento de la definición de tipo de documento (DTD). |
| [get_Schemas](./get_schemas/)() | Devuelve el XmlSchemaSet que se utilizará al realizar la validación de esquemas. |
| [get_ValidationFlags](./get_validationflags/)() | Devuelve un valor que indica la configuración de validación de esquemas. Esta configuración se aplica a los objetos [XmlReader](../xmlreader/) que validan esquemas (el valor de [XmlReaderSettings::get_ValidationType](./get_validationtype/) es [ValidationType::Schema](../validationtype/)). |
| [get_ValidationType](./get_validationtype/)() | Devuelve un valor que indica si el [XmlReader](../xmlreader/) realizará la validación o asignación de tipos al leer. |
| [Reset](./reset/)() | Restablece los miembros de la clase de configuración a sus valores predeterminados. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Establece un valor que indica si se debe realizar la comprobación de caracteres. |
| [set_CloseInput](./set_closeinput/)(bool) | Establece un valor que indica si el flujo subyacente o TextReader debe cerrarse cuando se cierra el lector. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Establece el nivel de conformidad al que se ajustará el [XmlReader](../xmlreader/). |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Establece un valor que determina el procesamiento de los DTD. |
| [set_IgnoreComments](./set_ignorecomments/)(bool) | Establece un valor que indica si se deben ignorar los comentarios. |
| [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(bool) | Establece un valor que indica si se deben ignorar las instrucciones de procesamiento. |
| [set_IgnoreWhitespace](./set_ignorewhitespace/)(bool) | Establece un valor que indica si se debe ignorar el espacio en blanco insignificante. |
| [set_LineNumberOffset](./set_linenumberoffset/)(int32_t) | Establece el desplazamiento del número de línea del objeto [XmlReader](../xmlreader/). |
| [set_LinePositionOffset](./set_linepositionoffset/)(int32_t) | Establece el desplazamiento de posición de línea del objeto [XmlReader](../xmlreader/). |
| [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(int64_t) | Establece un valor que indica el número máximo permitido de caracteres en un documento que resultan de la expansión de entidades. |
| [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(int64_t) | Establece un valor que indica el número máximo permitido de caracteres en un documento XML. Un valor cero (0) significa que no hay límites en el tamaño del documento XML. Un valor distinto de cero especifica el tamaño máximo, en caracteres. |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Establece la [XmlNameTable](../xmlnametable/) utilizada para comparaciones de cadenas atomizadas. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Establece un valor que indica si se debe prohibir el procesamiento de definiciones de tipo de documento (DTD). |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Establece el XmlSchemaSet a usar al realizar la validación de esquemas. |
| [set_ValidationFlags](./set_validationflags/)(Schema::XmlSchemaValidationFlags) | Establece un valor que indica la configuración de validación de esquemas. Esta configuración se aplica a los objetos [XmlReader](../xmlreader/) que validan esquemas (el valor de [XmlReaderSettings::get_ValidationType](./get_validationtype/) es [ValidationType::Schema](../validationtype/)). |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Establece un valor que indica si el [XmlReader](../xmlreader/) realizará validación o asignación de tipo al leer. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el [XmlResolver](../xmlresolver/) utilizado para acceder a documentos externos. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Agrega un controlador de eventos que se produce cuando el lector encuentra errores de validación. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un controlador de eventos que se produce cuando el lector encuentra errores de validación. |
| [XmlReaderSettings](./xmlreadersettings/)() | Inicializa una nueva instancia de la clase [XmlReaderSettings](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
