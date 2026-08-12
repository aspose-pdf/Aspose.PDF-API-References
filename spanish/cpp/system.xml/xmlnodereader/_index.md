---
title: "Clase System::Xml::XmlNodeReader"
linktitle: "XmlNodeReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlNodeReader. Representa un lector que proporciona acceso rápido, sin caché y solo de avance a los datos XML en un XmlNode en C++."
type: docs
weight: 2800
url: /es/cpp/system.xml/xmlnodereader/
---
## XmlNodeReader class


Representa un lector que proporciona acceso rápido, sin caché y solo de avance a los datos XML en un [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cambia el [XmlNodeReader::get_ReadState](./get_readstate/) a [ReadState::Closed](../readstate/). |
| [get_AttributeCount](./get_attributecount/)() override | Devuelve el número de atributos del nodo actual. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve la URI base del nodo actual. |
| [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Devuelve un valor que indica si el [XmlNodeReader](./) implementa los métodos de lectura de contenido binario. |
| [get_CanResolveEntity](./get_canresolveentity/)() override | Devuelve un valor que indica si este lector puede analizar y resolver entidades. |
| [get_Depth](./get_depth/)() override | Devuelve la profundidad del nodo actual en el documento XML. |
| [get_EOF](./get_eof/)() override | Devuelve un valor que indica si el lector está posicionado al final del flujo. |
| [get_HasAttributes](./get_hasattributes/)() override | Devuelve un valor que indica si el nodo actual tiene algún atributo. |
| [get_HasValue](./get_hasvalue/)() override | Devuelve un valor que indica si el nodo actual puede tener un valor de [XmlNodeReader::get_Value](./get_value/). |
| [get_IsDefault](./get_isdefault/)() override | Devuelve un valor que indica si el nodo actual es un atributo generado a partir del valor predeterminado definido en la definición de tipo de documento (DTD) o esquema. |
| [get_IsEmptyElement](./get_isemptyelement/)() override | Devuelve un valor que indica si el nodo actual es un elemento vacío (por ejemplo, **<MyElement/>**). |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo actual. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo actual. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Devuelve la URI del espacio de nombres (según la especificación de espacios de nombres de W3C) del nodo en el que está posicionado el lector. |
| [get_NameTable](./get_nametable/)() override | Devuelve la [XmlNameTable](../xmlnametable/) asociada con esta implementación. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_Prefix](./get_prefix/)() override | Devuelve el prefijo del espacio de nombres asociado al nodo actual. |
| [get_ReadState](./get_readstate/)() override | Devuelve el estado del lector. |
| [get_SchemaInfo](./get_schemainfo/)() override | Devuelve la información del esquema que se ha asignado al nodo actual. |
| [get_Value](./get_value/)() override | Devuelve el valor de texto del nodo actual. |
| [get_XmlLang](./get_xmllang/)() override | Devuelve el alcance actual de **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Devuelve el alcance actual de **xml:space**. |
| [GetAttribute](./getattribute/)(String) override | Devuelve el valor del atributo con el nombre especificado. |
| [GetAttribute](./getattribute/)(String, String) override | Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados. |
| [GetAttribute](./getattribute/)(int32_t) override | Devuelve el valor del atributo con el índice especificado. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Resuelve un prefijo de espacio de nombres en el alcance del elemento actual. |
| [MoveToAttribute](./movetoattribute/)(String) override | Se mueve al atributo con el nombre especificado. |
| [MoveToAttribute](./movetoattribute/)(String, String) override | Se mueve al atributo con el nombre local y el URI del espacio de nombres especificados. |
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
| [ResolveEntity](./resolveentity/)() override | Resuelve la referencia de entidad para los nodos **EntityReference**. |
| [Skip](./skip/)() override | Omite los hijos del nodo actual. |
| [XmlNodeReader](./xmlnodereader/)(const SharedPtr\<XmlNode\>\&) | Crea una instancia de la clase [XmlNodeReader](./) usando el [XmlNode](../xmlnode/) especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlReader](../xmlreader/)
* Class [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
