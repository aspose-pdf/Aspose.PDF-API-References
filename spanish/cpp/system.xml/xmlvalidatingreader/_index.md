---
title: "System::Xml::XmlValidatingReader clase"
linktitle: "XmlValidatingReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlValidatingReader clase. Representa un lector que proporciona validación de definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y lenguaje de definición de esquemas XML (XSD) en C++."
type: docs
weight: 4200
url: /es/cpp/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader class


Representa un lector que proporciona validación de definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y lenguaje de definición de [Schema](../../system.xml.schema/) XML (XSD).

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cambia el [XmlReader::get_ReadState](../xmlreader/get_readstate/) a Closed. |
| [get_AttributeCount](./get_attributecount/)() override | Devuelve el número de atributos del nodo actual. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve la URI base del nodo actual. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Devuelve un valor que indica si el [XmlValidatingReader](./) implementa los métodos de lectura de contenido binario. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Devuelve un valor que indica si este lector puede analizar y resolver entidades. |
| [get_Depth](./get_depth/)() override | Devuelve la profundidad del nodo actual en el documento XML. |
| [get_Encoding](./get_encoding/)() | Devuelve el atributo de codificación del documento. |
| [get_EntityHandling](./get_entityhandling/)() | Devuelve un valor que especifica cómo el lector maneja las entidades. |
| [get_EOF](./get_eof/)() override | Devuelve un valor que indica si el lector está posicionado al final del flujo. |
| [get_HasValue](./get_hasvalue/)() override | Devuelve un valor que indica si el nodo actual puede tener un [XmlValidatingReader::get_Value](./get_value/) distinto de [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Devuelve un valor que indica si el nodo actual es un atributo generado a partir del valor predeterminado definido en la definición de tipo de documento (DTD) o esquema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Devuelve un valor que indica si el nodo actual es un elemento vacío (por ejemplo, **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Devuelve el número de línea actual. |
| [get_LinePosition](./get_lineposition/)() override | Devuelve la posición de línea actual. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo actual. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo actual. |
| [get_Namespaces](./get_namespaces/)() | Devuelve un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve el Identificador Uniforme de Recursos (URI) del espacio de nombres (según lo definido en la especificación de espacios de nombres del Consorcio de la World Wide [Web](../../system.web/) (W3C)) del nodo en el que está posicionado el lector. |
| [get_NameTable](./get_nametable/)() override | Devuelve la [XmlNameTable](../xmlnametable/) asociada con esta implementación. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Prefix](./get_prefix/)() override | Devuelve el prefijo del espacio de nombres asociado al nodo actual. |
| [get_QuoteChar](./get_quotechar/)() override | Devuelve el carácter de comilla utilizado para encerrar el valor de un nodo de atributo. |
| [get_Reader](./get_reader/)() | Devuelve el [XmlReader](../xmlreader/) usado para construir este [XmlValidatingReader](./). |
| [get_ReadState](./get_readstate/)() override | Devuelve el estado del lector. |
| [get_Schemas](./get_schemas/)() | Devuelve una XmlSchemaCollection para usar en la validación. |
| [get_SchemaType](./get_schematype/)() | Devuelve un objeto de tipo de esquema. |
| [get_ValidationType](./get_validationtype/)() | Devuelve un valor que indica el tipo de validación a realizar. |
| [get_Value](./get_value/)() override | Devuelve el valor de texto del nodo actual. |
| [get_XmlLang](./get_xmllang/)() override | Devuelve el alcance actual de **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Devuelve el alcance actual de **xml:space**. |
| [GetAttribute](./getattribute/)(String) override | Devuelve el valor del atributo con el nombre especificado. |
| [GetAttribute](./getattribute/)(String, String) override | Devuelve el valor del atributo con el nombre local y el Identificador Uniforme de Recursos (URI) de espacio de nombres especificados. |
| [GetAttribute](./getattribute/)(int32_t) override | Devuelve el valor del atributo con el índice especificado. |
| [HasLineInfo](./haslineinfo/)() override | Devuelve un valor que indica si la clase puede devolver información de línea. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resuelve un prefijo de espacio de nombres en el alcance del elemento actual. |
| [MoveToAttribute](./movetoattribute/)(String) override | Se mueve al atributo con el nombre especificado. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Se mueve al atributo con el nombre local y el Identificador Uniforme de Recursos (URI) de espacio de nombres especificados. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Se mueve al atributo con el índice especificado. |
| [MoveToElement](./movetoelement/)() override | Se mueve al elemento que contiene el nodo de atributo actual. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Se mueve al primer atributo. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Se mueve al siguiente atributo. |
| [Read](./read/)() override | Lee el siguiente nodo del flujo. |
| [ReadAttributeValue](./readattributevalue/)() override | Analiza el valor del atributo en uno o más nodos **[Text](../../system.text/)**, **EntityReference** o **EndEntity**. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el contenido y devuelve los bytes binarios decodificados en Base64. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el contenido y devuelve los bytes binarios decodificados en BinHex. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el elemento y decodifica el contenido en Base64. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el elemento y decodifica el contenido en BinHex. |
| [ReadString](./readstring/)() override | Lee el contenido de un elemento o nodo de texto como una cadena. |
| [ReadTypedValue](./readtypedvalue/)() | Devuelve el tipo de tiempo de ejecución para el tipo de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD) especificado. |
| [ResolveEntity](./resolveentity/)() override | Resuelve la referencia de entidad para los nodos **EntityReference**. |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Establece un valor que especifica cómo el lector maneja las entidades. |
| [set_Namespaces](./set_namespaces/)(bool) | Establece un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | Establece un valor que indica el tipo de validación a realizar. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el [XmlResolver](../xmlresolver/) usado para resolver referencias externas de definición de tipo de documento (DTD) y de ubicación de esquemas. El [XmlResolver](../xmlresolver/) también se usa para manejar cualquier elemento import o include encontrado en esquemas XML [Schema](../../system.xml.schema/) (XSD). |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Agrega un controlador de eventos para recibir información sobre errores de validación de definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y esquema XML [Schema](../../system.xml.schema/) (XSD). |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Elimina un controlador de eventos para recibir información sobre errores de validación de definición de tipo de documento (DTD), esquema XML-Data Reduced (XDR) y esquema XML [Schema](../../system.xml.schema/) (XSD). |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<XmlReader\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) que valida el contenido devuelto por el [XmlReader](../xmlreader/) proporcionado. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) con los valores especificados. |
| [XmlValidatingReader](./xmlvalidatingreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Inicializa una nueva instancia de la clase [XmlValidatingReader](./) con los valores especificados. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones


## Deprecated
Esta clase está obsoleta. Se recomienda usar la clase XmlReaderSettings y el método XmlReader::Create para crear un lector XML de validación.

Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
