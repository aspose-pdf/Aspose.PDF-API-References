---
title: "Clase System::Xml::XmlTextReader"
linktitle: "XmlTextReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlTextReader. Representa un lector que proporciona acceso rápido, sin caché y solo hacia adelante a datos XML en C++."
type: docs
weight: 3900
url: /es/cpp/system.xml/xmltextreader/
---
## XmlTextReader class


Representa un lector que proporciona acceso rápido, sin caché y solo hacia adelante a datos XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cambia el [XmlReader::get_ReadState](../xmlreader/get_readstate/) a **Closed**. |
| [get_AttributeCount](./get_attributecount/)() override | Devuelve el número de atributos del nodo actual. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve la URI base del nodo actual. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Devuelve un valor que indica si el [XmlTextReader](./) implementa los métodos de lectura de contenido binario. |
| [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Devuelve un valor que indica si el [XmlTextReader](./) implementa el método [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Devuelve un valor que indica si este lector puede analizar y resolver entidades. |
| [get_Depth](./get_depth/)() override | Devuelve la profundidad del nodo actual en el documento XML. |
| [get_DtdProcessing](./get_dtdprocessing/)() | Devuelve la enumeración [DtdProcessing](../dtdprocessing/). |
| [get_Encoding](./get_encoding/)() | Devuelve la codificación del documento. |
| [get_EntityHandling](./get_entityhandling/)() | Devuelve un valor que especifica cómo el lector maneja las entidades. |
| [get_EOF](./get_eof/)() override | Devuelve un valor que indica si el lector está posicionado al final del flujo. |
| [get_HasValue](./get_hasvalue/)() override | Devuelve un valor que indica si el nodo actual puede tener un [XmlTextReader::get_Value](./get_value/) distinto de [String::Empty](../../system/string/empty/). |
| [get_IsDefault](./get_isdefault/)() override | Devuelve un valor que indica si el nodo actual es un atributo que fue generado a partir del valor predeterminado definido en el DTD o esquema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Devuelve un valor que indica si el nodo actual es un elemento vacío (por ejemplo, **<MyElement/>**). |
| [get_LineNumber](./get_linenumber/)() override | Devuelve el número de línea actual. |
| [get_LinePosition](./get_lineposition/)() override | Devuelve la posición de línea actual. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo actual. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo actual. |
| [get_Namespaces](./get_namespaces/)() | Devuelve un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve la URI del espacio de nombres (según la especificación de espacios de nombres de W3C) del nodo en el que está posicionado el lector. |
| [get_NameTable](./get_nametable/)() override | Devuelve la [XmlNameTable](../xmlnametable/) asociada con esta implementación. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Normalization](./get_normalization/)() | Devuelve un valor que indica si se normaliza el espacio en blanco y los valores de los atributos. |
| [get_Prefix](./get_prefix/)() override | Devuelve el prefijo del espacio de nombres asociado al nodo actual. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Devuelve un valor que indica si se permite el procesamiento de DTD. |
| [get_QuoteChar](./get_quotechar/)() override | Devuelve el carácter de comilla utilizado para encerrar el valor de un nodo de atributo. |
| [get_ReadState](./get_readstate/)() override | Devuelve el estado del lector. |
| [get_Value](./get_value/)() override | Devuelve el valor de texto del nodo actual. |
| [get_WhitespaceHandling](./get_whitespacehandling/)() | Devuelve un valor que especifica cómo se maneja el espacio en blanco. |
| [get_XmlLang](./get_xmllang/)() override | Devuelve el alcance actual de **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Devuelve el alcance actual de **xml:space**. |
| [GetAttribute](./getattribute/)(String) override | Devuelve el valor del atributo con el nombre especificado. |
| [GetAttribute](./getattribute/)(String, String) override | Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados. |
| [GetAttribute](./getattribute/)(int32_t) override | Devuelve el valor del atributo con el índice especificado. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Devuelve una colección que contiene todos los espacios de nombres actualmente en alcance. |
| [GetRemainder](./getremainder/)() | Devuelve el resto del XML almacenado en búfer. |
| [HasLineInfo](./haslineinfo/)() override | Devuelve un valor que indica si la clase puede devolver información de línea. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resuelve un prefijo de espacio de nombres en el alcance del elemento actual. |
| [MoveToAttribute](./movetoattribute/)(String) override | Se mueve al atributo con el nombre especificado. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Se mueve al atributo con el nombre local y el URI del espacio de nombres especificados. |
| [MoveToAttribute](./movetoattribute/)(int32_t) override | Se mueve al atributo con el índice especificado. |
| [MoveToElement](./movetoelement/)() override | Se mueve al elemento que contiene el nodo de atributo actual. |
| [MoveToFirstAttribute](./movetofirstattribute/)() override | Se mueve al primer atributo. |
| [MoveToNextAttribute](./movetonextattribute/)() override | Se mueve al siguiente atributo. |
| [Read](./read/)() override | Lee el siguiente nodo del flujo. |
| [ReadAttributeValue](./readattributevalue/)() override | Analiza el valor del atributo en uno o más nodos **[Text](../../system.text/)**, **EntityReference** o **EndEntity**. |
| [ReadBase64](./readbase64/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodifica Base64 y devuelve los bytes binarios decodificados. |
| [ReadBinHex](./readbinhex/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Decodifica **BinHex** y devuelve los bytes binarios decodificados. |
| [ReadChars](./readchars/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) | Lee el contenido de texto de un elemento en un búfer de caracteres. Este método está diseñado para leer grandes flujos de texto incrustado llamándolo sucesivamente. |
| [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el contenido y devuelve los bytes binarios decodificados en **Base64**. |
| [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el contenido y devuelve los bytes binarios decodificados en **BinHex**. |
| [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el elemento y decodifica el contenido en Base64. |
| [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Lee el elemento y decodifica el contenido **BinHex**. |
| [ReadString](./readstring/)() override | Lee el contenido de un elemento o de un nodo de texto como una cadena. |
| [ResetState](./resetstate/)() | Restablece el estado del lector a [ReadState::Initial](../readstate/). |
| [ResolveEntity](./resolveentity/)() override | Resuelve la referencia de entidad para los nodos **EntityReference**. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | Establece la enumeración [DtdProcessing](../dtdprocessing/). |
| [set_EntityHandling](./set_entityhandling/)(System::Xml::EntityHandling) | Establece un valor que especifica cómo el lector maneja las entidades. |
| [set_Namespaces](./set_namespaces/)(bool) | Establece un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [set_Normalization](./set_normalization/)(bool) | Establece un valor que indica si se debe normalizar el espacio en blanco y los valores de los atributos. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Establece un valor que indica si se permite el procesamiento de DTD. |
| [set_WhitespaceHandling](./set_whitespacehandling/)(System::Xml::WhitespaceHandling) | Establece un valor que especifica cómo se maneja el espacio en blanco. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Establece el [XmlResolver](../xmlresolver/) utilizado para resolver referencias DTD. |
| [Skip](./skip/)() override | Omite los hijos del nodo actual. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el flujo especificado. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con la URL y el flujo especificados. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el flujo especificado y [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con la URL, el flujo y [XmlNameTable](../xmlnametable/) especificados. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el TextReader especificado. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con la URL y el TextReader especificados. |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el TextReader especificado y [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con la URL especificada, TextReader y [XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el flujo especificado, [XmlNodeType](../xmlnodetype/), y [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con la cadena especificada, [XmlNodeType](../xmlnodetype/), y [XmlParserContext](../xmlparsercontext/). |
| [XmlTextReader](./xmltextreader/)(const String\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el archivo especificado. |
| [XmlTextReader](./xmltextreader/)(const String\&, const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlTextReader](./) con el archivo especificado y [XmlNameTable](../xmlnametable/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Se recomienda usar la clase [XmlReader](../xmlreader/) en su lugar.

Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlReader](../xmlreader/)
* Class [IXmlLineInfo](../ixmllineinfo/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
