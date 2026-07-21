---
title: "Clase System::Xml::XmlWriter"
linktitle: "XmlWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlWriter. Representa un escritor que proporciona una forma rápida, sin caché y solo de avance para generar flujos o archivos que contienen datos XML en C++."
type: docs
weight: 4400
url: /es/cpp/system.xml/xmlwriter/
---
## XmlWriter class


Representa un escritor que proporciona una forma rápida, sin caché y solo de avance para generar flujos o archivos que contienen datos XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Cuando se sobrescribe en una clase derivada, cierra este flujo y el flujo subyacente. |
| static [Create](./create/)(const String\&) | Crea una nueva instancia de [XmlWriter](./) usando el nombre de archivo especificado. |
| static [Create](./create/)(const String\&, SharedPtr\<XmlWriterSettings\>) | Crea una nueva instancia de [XmlWriter](./) usando el nombre de archivo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el flujo especificado. |
| static [Create](./create/)(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) | Crea una nueva instancia de [XmlWriter](./) usando el flujo y el objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el TextWriter especificado. |
| static [Create](./create/)(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Crea una nueva instancia de [XmlWriter](./) usando el TextWriter y los objetos [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el [Text::StringBuilder](../../system.text/stringbuilder/) especificado. |
| static [Create](./create/)(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) | Crea una nueva instancia de [XmlWriter](./) usando el [Text::StringBuilder](../../system.text/stringbuilder/) y los objetos [XmlWriterSettings](../xmlwritersettings/). |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&) | Crea una nueva instancia de [XmlWriter](./) usando el objeto [XmlWriter](./) especificado. |
| static [Create](./create/)(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) | Crea una nueva instancia de [XmlWriter](./) usando los objetos [XmlWriter](./) y [XmlWriterSettings](../xmlwritersettings/) especificados. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por la instancia actual de la clase [XmlWriter](./). |
| virtual [Flush](./flush/)() | Cuando se sobrescribe en una clase derivada, vacía lo que haya en el búfer a los flujos subyacentes y también vacía el flujo subyacente. |
| virtual [get_Settings](./get_settings/)() | Devuelve el objeto [XmlWriterSettings](../xmlwritersettings/) utilizado para crear esta instancia de [XmlWriter](./). |
| virtual [get_WriteState](./get_writestate/)() | Cuando se sobrescribe en una clase derivada, obtiene el estado del escritor. |
| virtual [get_XmlLang](./get_xmllang/)() | Cuando se sobrescribe en una clase derivada, obtiene el alcance actual de **xml:lang**. |
| virtual [get_XmlSpace](./get_xmlspace/)() | Cuando se sobrescribe en una clase derivada, obtiene un [XmlSpace](../xmlspace/) que representa el ámbito actual de **xml:space**. |
| virtual [LookupPrefix](./lookupprefix/)(String) | Cuando se sobrescribe en una clase derivada, devuelve el prefijo más cercano definido en el ámbito de espacio de nombres actual para el URI del espacio de nombres. |
| virtual [WriteAttributes](./writeattributes/)(SharedPtr\<XmlReader\>, bool) | Cuando se sobrescribe en una clase derivada, escribe todos los atributos encontrados en la posición actual del [XmlReader](../xmlreader/). |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe un atributo con el nombre local, el URI del espacio de nombres y el valor especificados. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el nombre local y el valor especificados. |
| [WriteAttributeString](./writeattributestring/)(const String\&, const String\&, const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe el atributo con el prefijo, el nombre local, el URI del espacio de nombres y el valor especificados. |
| virtual [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Cuando se sobrescribe en una clase derivada, codifica los bytes binarios especificados como Base64 y escribe el texto resultante. |
| virtual [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) | Cuando se sobrescribe en una clase derivada, codifica los bytes binarios especificados como **BinHex** y escribe el texto resultante. |
| virtual [WriteCData](./writecdata/)(String) | Cuando se sobrescribe en una clase derivada, escribe un bloque **...** que contiene el texto especificado. |
| virtual [WriteCharEntity](./writecharentity/)(char16_t) | Cuando se sobrescribe en una clase derivada, fuerza la generación de una entidad de carácter para el valor Unicode del carácter especificado. |
| virtual [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | Cuando se sobrescribe en una clase derivada, escribe texto un búfer a la vez. |
| virtual [WriteComment](./writecomment/)(String) | Cuando se sobrescribe en una clase derivada, escribe un comentario **** que contiene el texto especificado. |
| virtual [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&) | Escribe un elemento con el nombre local y el valor especificados. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&) | Escribe un elemento con el nombre local, el URI del espacio de nombres y el valor especificados. |
| [WriteElementString](./writeelementstring/)(const String\&, const String\&, const String\&, const String\&) | Escribe un elemento con el prefijo, el nombre local, el URI del espacio de nombres y el valor especificados. |
| virtual [WriteEndAttribute](./writeendattribute/)() | Cuando se sobrescribe en una clase derivada, cierra la llamada anterior a XmlWriter::WriteStartAttribute(String,String). |
| virtual [WriteEndDocument](./writeenddocument/)() | Cuando se sobrescribe en una clase derivada, cierra cualquier elemento o atributo abierto y devuelve el escritor al estado Start. |
| virtual [WriteEndElement](./writeendelement/)() | Cuando se sobrescribe en una clase derivada, cierra un elemento y elimina el ámbito de espacio de nombres correspondiente. |
| virtual [WriteEntityRef](./writeentityref/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe una referencia de entidad como **&name**;. |
| virtual [WriteFullEndElement](./writefullendelement/)() | Cuando se sobrescribe en una clase derivada, cierra un elemento y elimina el ámbito de espacio de nombres correspondiente. |
| virtual [WriteName](./writename/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre especificado, asegurándose de que sea un nombre válido según la recomendación W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNmToken](./writenmtoken/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre especificado, asegurándose de que sea un NmToken válido según la recomendación W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual [WriteNode](./writenode/)(SharedPtr\<XmlReader\>, bool) | Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y mueve el lector al inicio del siguiente hermano. |
| virtual [WriteNode](./writenode/)(SharedPtr\<XPath::XPathNavigator\>, bool) | Copia todo del objeto XPathNavigator al escritor. La posición del XPathNavigator permanece sin cambios. |
| virtual [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) | Cuando se sobrescribe en una clase derivada, escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente manera: **<?name text?>**. |
| virtual [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe el nombre calificado con espacio de nombres. Este método busca el prefijo que está en alcance para el espacio de nombres dado. |
| virtual [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) | Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde un búfer de caracteres. |
| virtual [WriteRaw](./writeraw/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde una cadena. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&) | Escribe el inicio de un atributo con el nombre local especificado y el URI del espacio de nombres. |
| virtual [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe el inicio de un atributo con el prefijo especificado, el nombre local y el URI del espacio de nombres. |
| [WriteStartAttribute](./writestartattribute/)(const String\&) | Escribe el inicio de un atributo con el nombre local especificado. |
| virtual [WriteStartDocument](./writestartdocument/)() | Cuando se sobrescribe en una clase derivada, escribe la declaración XML con la versión "1.0". |
| virtual [WriteStartDocument](./writestartdocument/)(bool) | Cuando se sobrescribe en una clase derivada, escribe la declaración XML con la versión "1.0" y el atributo standalone. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres dado. |
| virtual [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) | Cuando se sobrescribe en una clase derivada, escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y el prefijo dados. |
| [WriteStartElement](./writestartelement/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe una etiqueta de inicio con el nombre local especificado. |
| virtual [WriteString](./writestring/)(const String\&) | Cuando se sobrescribe en una clase derivada, escribe el contenido de texto proporcionado. |
| virtual [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Cuando se sobrescribe en una clase derivada, genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos. |
| virtual [WriteValue](./writevalue/)(SharedPtr\<Object\>) | Escribe el valor del objeto. |
| virtual [WriteValue](./writevalue/)(const String\&) | Escribe un valor de [String](../../system/string/). |
| virtual [WriteValue](./writevalue/)(bool) | Escribe un valor de [Boolean](../../system/boolean/). |
| virtual [WriteValue](./writevalue/)(DateTime) | Escribe un valor de [DateTime](../../system/datetime/). |
| virtual [WriteValue](./writevalue/)(DateTimeOffset) | Escribe un valor de [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [WriteValue](./writevalue/)(double) | Escribe un valor de [Double](../../system/double/). |
| virtual [WriteValue](./writevalue/)(float) | Escribe un número de punto flotante de precisión simple. |
| virtual [WriteValue](./writevalue/)(Decimal) | Escribe un valor de [Decimal](../../system/decimal/). |
| virtual [WriteValue](./writevalue/)(int32_t) | Escribe un valor de [Int32](../../system/int32/). |
| virtual [WriteValue](./writevalue/)(int64_t) | Escribe un valor [Int64](../../system/int64/). |
| virtual [WriteWhitespace](./writewhitespace/)(String) | Cuando se sobrescribe en una clase derivada, escribe el espacio en blanco proporcionado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
