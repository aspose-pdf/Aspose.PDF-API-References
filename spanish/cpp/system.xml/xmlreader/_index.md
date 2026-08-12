---
title: "System::Xml::XmlReader clase"
linktitle: "XmlReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlReader clase. Representa un lector que proporciona acceso rápido, sin caché y solo hacia adelante a los datos XML en C++."
type: docs
weight: 3300
url: /es/cpp/system.xml/xmlreader/
---
## XmlReader class


Representa un lector que proporciona acceso rápido, sin caché y solo hacia adelante a datos XML.

```cpp
class XmlReader : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cuando se sobrescribe en una clase derivada, cambia el [XmlReader::get_ReadState](./get_readstate/) a [ReadState::Closed](../readstate/). |
| static [Create](./create/)(const String\&) | Crea una nueva instancia de [XmlReader](./) con la URI especificada. |
| static [Create](./create/)(const String\&, const SharedPtr\<XmlReaderSettings\>\&) | Crea una nueva instancia de [XmlReader](./) usando la URI y la configuración especificadas. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Crea una nueva instancia de [XmlReader](./) usando la URI, la configuración y la información de contexto especificadas para el análisis. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Crea una nueva instancia de [XmlReader](./) usando el flujo especificado con la configuración predeterminada. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) | Crea una nueva instancia de [XmlReader](./) con el flujo y la configuración especificados. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) | Crea una nueva instancia de [XmlReader](./) usando el flujo, la URI base y la configuración especificados. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Crea una nueva instancia de [XmlReader](./) usando el flujo, la configuración y la información de contexto especificados para el análisis. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&) | Crea una nueva instancia de [XmlReader](./) usando el lector de texto especificado. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) | Crea una nueva instancia de [XmlReader](./) usando el lector de texto y la configuración especificados. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) | Crea una nueva instancia de [XmlReader](./) usando el lector de texto, la configuración y la URI base especificados. |
| static [Create](./create/)(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) | Crea una nueva instancia de [XmlReader](./) usando el lector de texto, la configuración y la información de contexto especificados para el análisis. |
| static [Create](./create/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) | Crea una nueva instancia de [XmlReader](./) usando el lector XML y la configuración especificados. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por la instancia actual de la clase [XmlReader](./). |
| virtual [get_AttributeCount](./get_attributecount/)() | Cuando se sobrescribe en una clase derivada, obtiene el número de atributos del nodo actual. |
| virtual [get_BaseURI](./get_baseuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI base del nodo actual. |
| virtual [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Devuelve un valor que indica si el [XmlReader](./) implementa los métodos de lectura de contenido binario. |
| virtual [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Devuelve un valor que indica si el [XmlReader](./) implementa el método [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual [get_CanResolveEntity](./get_canresolveentity/)() | Devuelve un valor que indica si este lector puede analizar y resolver entidades. |
| virtual [get_Depth](./get_depth/)() | Cuando se sobrescribe en una clase derivada, obtiene la profundidad del nodo actual en el documento XML. |
| virtual [get_EOF](./get_eof/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el lector está posicionado al final del flujo. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Devuelve un valor que indica si el nodo actual tiene algún atributo. |
| virtual [get_HasValue](./get_hasvalue/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el nodo actual puede tener un valor de [XmlReader::get_Value](./get_value/). |
| virtual [get_IsDefault](./get_isdefault/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el nodo actual es un atributo que fue generado a partir del valor predeterminado definido en el DTD o esquema. |
| virtual [get_IsEmptyElement](./get_isemptyelement/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el nodo actual es un elemento vacío (por ejemplo, **<MyElement/>**). |
| virtual [get_LocalName](./get_localname/)() | Cuando se sobrescribe en una clase derivada, obtiene el nombre local del nodo actual. |
| virtual [get_Name](./get_name/)() | Cuando se sobrescribe en una clase derivada, obtiene el nombre calificado del nodo actual. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI del espacio de nombres (según lo definido en la especificación de espacios de nombres de W3C) del nodo en el que está posicionado el lector. |
| virtual [get_NameTable](./get_nametable/)() | Cuando se sobrescribe en una clase derivada, obtiene la [XmlNameTable](../xmlnametable/) asociada con esta implementación. |
| virtual [get_NodeType](./get_nodetype/)() | Cuando se sobrescribe en una clase derivada, obtiene el tipo del nodo actual. |
| virtual [get_Prefix](./get_prefix/)() | Cuando se sobrescribe en una clase derivada, obtiene el prefijo del espacio de nombres asociado con el nodo actual. |
| virtual [get_QuoteChar](./get_quotechar/)() | Cuando se sobrescribe en una clase derivada, obtiene el carácter de comilla utilizado para encerrar el valor de un nodo de atributo. |
| virtual [get_ReadState](./get_readstate/)() | Cuando se sobrescribe en una clase derivada, obtiene el estado del lector. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Devuelve la información del esquema que ha sido asignada al nodo actual como resultado de la validación del esquema. |
| virtual [get_Settings](./get_settings/)() | Devuelve el objeto [XmlReaderSettings](../xmlreadersettings/) utilizado para crear esta instancia de [XmlReader](./). |
| virtual [get_Value](./get_value/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor de texto del nodo actual. |
| virtual [get_ValueType](./get_valuetype/)() | Devuelve el tipo del nodo actual. |
| virtual [get_XmlLang](./get_xmllang/)() | Cuando se sobrescribe en una clase derivada, obtiene el alcance actual de **xml:lang**. |
| virtual [get_XmlSpace](./get_xmlspace/)() | Cuando se sobrescribe en una clase derivada, obtiene el alcance actual de **xml:space**. |
| virtual [GetAttribute](./getattribute/)(String) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el valor especificado de [XmlReader::get_Name](./get_name/). |
| virtual [GetAttribute](./getattribute/)(String, String) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con los valores especificados de [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual [GetAttribute](./getattribute/)(int32_t) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado. |
| virtual [idx_get](./idx_get/)(int32_t) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado. |
| virtual [idx_get](./idx_get/)(String) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el valor especificado de [XmlReader::get_Name](./get_name/). |
| virtual [idx_get](./idx_get/)(String, String) | Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con los valores especificados de [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| static [IsName](./isname/)(const String\&) | Devuelve un valor que indica si el argumento de cadena es un nombre XML válido. |
| static [IsNameToken](./isnametoken/)(const String\&) | Devuelve un valor que indica si el argumento de cadena es o no un token de nombre XML válido. |
| virtual [IsStartElement](./isstartelement/)() | Llama a [XmlReader::MoveToContent](./movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío. |
| virtual [IsStartElement](./isstartelement/)(String) | Llama a [XmlReader::MoveToContent](./movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si el valor de [XmlReader::get_Name](./get_name/) del elemento encontrado coincide con el argumento proporcionado. |
| virtual [IsStartElement](./isstartelement/)(String, String) | Llama a [XmlReader::MoveToContent](./movetocontent/) y verifica si el nodo de contenido actual es una etiqueta de inicio o una etiqueta de elemento vacío y si los valores de [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/) del elemento encontrado coinciden con las cadenas proporcionadas. |
| virtual [LookupNamespace](./lookupnamespace/)(const String\&) | Cuando se sobrescribe en una clase derivada, resuelve un prefijo de espacio de nombres en el ámbito del elemento actual. |
| virtual [MoveToAttribute](./movetoattribute/)(String) | Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el valor especificado de [XmlReader::get_Name](./get_name/). |
| virtual [MoveToAttribute](./movetoattribute/)(String, String) | Cuando se sobrescribe en una clase derivada, se desplaza al atributo con los valores especificados de [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual [MoveToAttribute](./movetoattribute/)(int32_t) | Cuando se sobrescribe en una clase derivada, se desplaza al atributo con el índice especificado. |
| virtual [MoveToContent](./movetocontent/)() | Verifica si el nodo actual es un nodo de contenido (texto sin espacios en blanco, **CDATA**, **Element**, **EndElement**, **EntityReference** o **EndEntity**). Si el nodo no es un nodo de contenido, el lector avanza hasta el siguiente nodo de contenido o el final del archivo. Omite los nodos del siguiente tipo: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** o **SignificantWhitespace**. |
| virtual [MoveToElement](./movetoelement/)() | Cuando se sobrescribe en una clase derivada, se desplaza al elemento que contiene el nodo de atributo actual. |
| virtual [MoveToFirstAttribute](./movetofirstattribute/)() | Cuando se sobrescribe en una clase derivada, se desplaza al primer atributo. |
| virtual [MoveToNextAttribute](./movetonextattribute/)() | Cuando se sobrescribe en una clase derivada, se desplaza al siguiente atributo. |
| virtual [Read](./read/)() | Cuando se sobrescribe en una clase derivada, lee el siguiente nodo del flujo. |
| virtual [ReadAttributeValue](./readattributevalue/)() | Cuando se sobrescribe en una clase derivada, analiza el valor del atributo en uno o más nodos **[Text](../../system.text/)**, **EntityReference** o **EndEntity**. |
| virtual [ReadContentAs](./readcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Lee el contenido como un objeto del tipo especificado. |
| virtual [ReadContentAsBase64](./readcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Lee el contenido y devuelve los bytes binarios decodificados en Base64. |
| virtual [ReadContentAsBinHex](./readcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Lee el contenido y devuelve los bytes binarios decodificados en **BinHex**. |
| virtual [ReadContentAsBoolean](./readcontentasboolean/)() | Lee el contenido de texto en la posición actual como un [Boolean](../../system/boolean/). |
| virtual [ReadContentAsDateTime](./readcontentasdatetime/)() | Lee el contenido de texto en la posición actual como un objeto [DateTime](../../system/datetime/). |
| virtual [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Lee el contenido de texto en la posición actual como un objeto [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [ReadContentAsDecimal](./readcontentasdecimal/)() | Lee el contenido de texto en la posición actual como un objeto [Decimal](../../system/decimal/). |
| virtual [ReadContentAsDouble](./readcontentasdouble/)() | Lee el contenido de texto en la posición actual como un número de punto flotante de doble precisión. |
| virtual [ReadContentAsFloat](./readcontentasfloat/)() | Lee el contenido de texto en la posición actual como un número de punto flotante de precisión simple. |
| virtual [ReadContentAsInt](./readcontentasint/)() | Lee el contenido de texto en la posición actual como un entero con signo de 32 bits. |
| virtual [ReadContentAsLong](./readcontentaslong/)() | Lee el contenido de texto en la posición actual como un entero con signo de 64 bits. |
| virtual [ReadContentAsObject](./readcontentasobject/)() | Lee el contenido de texto en la posición actual como un [Object](../../system/object/). |
| virtual [ReadContentAsString](./readcontentasstring/)() | Lee el contenido de texto en la posición actual como un objeto [String](../../system/string/) . |
| virtual [ReadElementContentAs](./readelementcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Lee el contenido del elemento como el tipo solicitado. |
| virtual [ReadElementContentAs](./readelementcontentas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el contenido del elemento como el tipo solicitado. |
| virtual [ReadElementContentAsBase64](./readelementcontentasbase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Lee el elemento y decodifica el contenido **Base64**. |
| virtual [ReadElementContentAsBinHex](./readelementcontentasbinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Lee el elemento y decodifica el contenido **BinHex**. |
| virtual [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Lee el elemento actual y devuelve el contenido como un objeto [Boolean](../../system/boolean/) . |
| virtual [ReadElementContentAsBoolean](./readelementcontentasboolean/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un objeto [Boolean](../../system/boolean/) . |
| virtual [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Lee el elemento actual y devuelve el contenido como un objeto [DateTime](../../system/datetime/) . |
| virtual [ReadElementContentAsDateTime](./readelementcontentasdatetime/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un objeto [DateTime](../../system/datetime/) . |
| virtual [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Lee el elemento actual y devuelve el contenido como un objeto [Decimal](../../system/decimal/) . |
| virtual [ReadElementContentAsDecimal](./readelementcontentasdecimal/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un objeto [Decimal](../../system/decimal/) . |
| virtual [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Lee el elemento actual y devuelve el contenido como un número de punto flotante de doble precisión. |
| virtual [ReadElementContentAsDouble](./readelementcontentasdouble/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un número de punto flotante de doble precisión. |
| virtual [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Lee el elemento actual y devuelve el contenido como un número de punto flotante de precisión simple. |
| virtual [ReadElementContentAsFloat](./readelementcontentasfloat/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un número de punto flotante de precisión simple. |
| virtual [ReadElementContentAsInt](./readelementcontentasint/)() | Lee el elemento actual y devuelve el contenido como un entero con signo de 32 bits. |
| virtual [ReadElementContentAsInt](./readelementcontentasint/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un entero con signo de 32 bits. |
| virtual [ReadElementContentAsLong](./readelementcontentaslong/)() | Lee el elemento actual y devuelve el contenido como un entero con signo de 64 bits. |
| virtual [ReadElementContentAsLong](./readelementcontentaslong/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un entero con signo de 64 bits. |
| virtual [ReadElementContentAsObject](./readelementcontentasobject/)() | Lee el elemento actual y devuelve el contenido como un [Object](../../system/object/) . |
| virtual [ReadElementContentAsObject](./readelementcontentasobject/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un [Object](../../system/object/) . |
| virtual [ReadElementContentAsString](./readelementcontentasstring/)() | Lee el elemento actual y devuelve el contenido como un objeto [String](../../system/string/) . |
| virtual [ReadElementContentAsString](./readelementcontentasstring/)(String, String) | Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el elemento actual y devuelve el contenido como un objeto [String](../../system/string/) . |
| virtual [ReadElementString](./readelementstring/)() | Lee un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [ReadElementString](./readelementstring/)(String) | Comprueba que el valor [XmlReader::get_Name](./get_name/) del elemento encontrado coincida con la cadena proporcionada antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [ReadElementString](./readelementstring/)(String, String) | Comprueba que los valores [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/) del elemento encontrado coincidan con las cadenas proporcionadas antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [ReadEndElement](./readendelement/)() | Comprueba que el nodo de contenido actual sea una etiqueta de cierre y avanza el lector al siguiente nodo. |
| virtual [ReadInnerXml](./readinnerxml/)() | Cuando se sobrescribe en una clase derivada, lee todo el contenido, incluido el marcado, como una cadena. |
| virtual [ReadOuterXml](./readouterxml/)() | Cuando se sobrescribe en una clase derivada, lee el contenido, incluido el marcado, que representa este nodo y todos sus hijos. |
| virtual [ReadStartElement](./readstartelement/)() | Comprueba que el nodo actual sea un elemento y avanza el lector al siguiente nodo. |
| virtual [ReadStartElement](./readstartelement/)(String) | Comprueba que el nodo de contenido actual sea un elemento con el valor [XmlReader::get_Name](./get_name/) proporcionado y avanza el lector al siguiente nodo. |
| virtual [ReadStartElement](./readstartelement/)(String, String) | Comprueba que el nodo de contenido actual sea un elemento con los valores [XmlReader::get_LocalName](./get_localname/) y [XmlReader::get_NamespaceURI](./get_namespaceuri/) proporcionados y avanza el lector al siguiente nodo. |
| virtual [ReadString](./readstring/)() | Cuando se sobrescribe en una clase derivada, lee el contenido de un elemento o nodo de texto como una cadena. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación. |
| virtual [ReadSubtree](./readsubtree/)() | Devuelve una nueva instancia de [XmlReader](./) que puede usarse para leer el nodo actual y todos sus descendientes. |
| virtual [ReadToDescendant](./readtodescendant/)(String) | Avanza el [XmlReader](./) al siguiente elemento descendiente con el nombre calificado especificado. |
| virtual [ReadToDescendant](./readtodescendant/)(String, String) | Avanza el [XmlReader](./) al siguiente elemento descendiente con el nombre local y el URI de espacio de nombres especificados. |
| virtual [ReadToFollowing](./readtofollowing/)(String) | Lee hasta que se encuentre un elemento con el nombre calificado especificado. |
| virtual [ReadToFollowing](./readtofollowing/)(String, String) | Lee hasta que se encuentre un elemento con el nombre local y el URI de espacio de nombres especificados. |
| virtual [ReadToNextSibling](./readtonextsibling/)(String) | Avanza el [XmlReader](./) al siguiente elemento hermano con el nombre calificado especificado. |
| virtual [ReadToNextSibling](./readtonextsibling/)(String, String) | Avanza el [XmlReader](./) al siguiente elemento hermano con el nombre local y el URI de espacio de nombres especificados. |
| virtual [ReadValueChunk](./readvaluechunk/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | Lee grandes flujos de texto incrustados en un documento XML. |
| virtual [ResolveEntity](./resolveentity/)() | Cuando se sobrescribe en una clase derivada, resuelve la referencia de entidad para los nodos **EntityReference**. |
| virtual [Skip](./skip/)() | Omite los hijos del nodo actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
