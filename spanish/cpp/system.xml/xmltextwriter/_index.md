---
title: "System::Xml::XmlTextWriter class"
linktitle: "XmlTextWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlTextWriter. Representa un escritor que proporciona una forma rápida, sin caché y solo de avance para generar flujos o archivos que contienen datos XML que cumplen con el Lenguaje de Marcado Extensible (XML) 1.0 del W3C y las recomendaciones de Namespaces in XML en C++."
type: docs
weight: 4000
url: /es/cpp/system.xml/xmltextwriter/
---
## XmlTextWriter class


Representa un escritor que proporciona una forma rápida, sin caché y solo hacia adelante de generar flujos o archivos que contengan datos XML que cumplan con las recomendaciones del W3C Extensible Markup Language (XML) 1.0 y Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cierra este flujo y el flujo subyacente. |
| [Flush](./flush/)() override | Descarga todo lo que está en el búfer a los flujos subyacentes y también descarga el flujo subyacente. |
| [get_BaseStream](./get_basestream/)() | Devuelve el objeto de flujo subyacente. |
| [get_Formatting](./get_formatting/)() | Indica cómo está formateada la salida. |
| [get_Indentation](./get_indentation/)() | Devuelve cuántos IndentChars escribir para cada nivel en la jerarquía cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| [get_IndentChar](./get_indentchar/)() | Devuelve qué carácter usar para la sangría cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| [get_Namespaces](./get_namespaces/)() | Devuelve un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [get_QuoteChar](./get_quotechar/)() | Devuelve qué carácter usar para citar los valores de los atributos. |
| [get_WriteState](./get_writestate/)() override | Devuelve el estado del escritor. |
| [get_XmlLang](./get_xmllang/)() override | Devuelve el alcance actual de **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() override | Devuelve un [XmlSpace](../xmlspace/) que representa el alcance actual de **xml:space**. |
| [LookupPrefix](./lookupprefix/)(String) override | Devuelve el prefijo más cercano definido en el alcance actual del espacio de nombres para el URI del espacio de nombres. |
| [set_Formatting](./set_formatting/)(System::Xml::Formatting) | Indica cómo está formateada la salida. |
| [set_Indentation](./set_indentation/)(int32_t) | Establece cuántos IndentChars escribir para cada nivel en la jerarquía cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| [set_IndentChar](./set_indentchar/)(char16_t) | Establece qué carácter usar para la sangría cuando [XmlTextWriter::set_Formatting](./set_formatting/) está configurado a [Formatting::Indented](../formatting/). |
| [set_Namespaces](./set_namespaces/)(bool) | Establece un valor que indica si se debe habilitar el soporte de espacios de nombres. |
| [set_QuoteChar](./set_quotechar/)(char16_t) | Establece qué carácter usar para citar los valores de los atributos. |
| [WriteBase64](./writebase64/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Codifica los bytes binarios especificados como base64 y escribe el texto resultante. |
| [WriteBinHex](./writebinhex/)(ArrayPtr\<uint8_t\>, int32_t, int32_t) override | Codifica los bytes binarios especificados como binhex y escribe el texto resultante. |
| [WriteCData](./writecdata/)(String) override | Escribe un bloque **...** que contiene el texto especificado. |
| [WriteCharEntity](./writecharentity/)(char16_t) override | Forza la generación de una entidad de carácter para el valor Unicode de carácter especificado. |
| [WriteChars](./writechars/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Escribe texto un búfer a la vez. |
| [WriteComment](./writecomment/)(String) override | Escribe un comentario **** que contiene el texto especificado. |
| [WriteDocType](./writedoctype/)(const String\&, const String\&, const String\&, const String\&) override | Escribe la declaración DOCTYPE con el nombre especificado y atributos opcionales. |
| [WriteEndAttribute](./writeendattribute/)() override | Cierra la llamada anterior a [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| [WriteEndDocument](./writeenddocument/)() override | Cierra cualquier elemento o atributo abierto y devuelve el escritor al estado Start. |
| [WriteEndElement](./writeendelement/)() override | Cierra un elemento y elimina el alcance del espacio de nombres correspondiente. |
| [WriteEntityRef](./writeentityref/)(const String\&) override | Escribe una referencia de entidad como **&name**;. |
| [WriteFullEndElement](./writefullendelement/)() override | Cierra un elemento y elimina el alcance del espacio de nombres correspondiente. |
| [WriteName](./writename/)(const String\&) override | Escribe el nombre especificado, asegurándose de que sea un nombre válido según la [recomendación W3C XML 1.0](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteNmToken](./writenmtoken/)(const String\&) override | Escribe el nombre especificado, asegurándose de que sea un **NmToken** válido según la [recomendación W3C XML 1.0](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| [WriteProcessingInstruction](./writeprocessinginstruction/)(String, String) override | Escribe una instrucción de procesamiento con un espacio entre el nombre y el texto de la siguiente manera: **<?name text?>**. |
| [WriteQualifiedName](./writequalifiedname/)(const String\&, const String\&) override | Escribe el nombre calificado por espacio de nombres. Este método busca el prefijo que está en alcance para el espacio de nombres dado. |
| [WriteRaw](./writeraw/)(ArrayPtr\<char16_t\>, int32_t, int32_t) override | Escribe marcado sin procesar manualmente desde un búfer de caracteres. |
| [WriteRaw](./writeraw/)(const String\&) override | Escribe marcado sin procesar manualmente desde una cadena. |
| [WriteStartAttribute](./writestartattribute/)(const String\&, const String\&, const String\&) override | Escribe el inicio de un atributo. |
| [WriteStartDocument](./writestartdocument/)() override | Escribe la declaración XML con la versión "1.0". |
| [WriteStartDocument](./writestartdocument/)(bool) override | Escribe la declaración XML con la versión "1.0" y el atributo standalone. |
| [WriteStartElement](./writestartelement/)(const String\&, const String\&, const String\&) override | Escribe la etiqueta de inicio especificada y la asocia con el espacio de nombres y prefijo dados. |
| [WriteString](./writestring/)(const String\&) override | Escribe el contenido de texto proporcionado. |
| [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Genera y escribe la entidad de carácter sustituto para el par de caracteres sustitutos. |
| [WriteWhitespace](./writewhitespace/)(String) override | Escribe el espacio en blanco proporcionado. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el flujo y la codificación especificados. |
| [XmlTextWriter](./xmltextwriter/)(const String\&, const SharedPtr\<Text::Encoding\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el archivo especificado. |
| [XmlTextWriter](./xmltextwriter/)(const SharedPtr\<IO::TextWriter\>\&) | Crea una instancia de la clase [XmlTextWriter](./) usando el TextWriter especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Se recomienda usar la clase [XmlWriter](../xmlwriter/) en su lugar.

Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlWriter](../xmlwriter/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
