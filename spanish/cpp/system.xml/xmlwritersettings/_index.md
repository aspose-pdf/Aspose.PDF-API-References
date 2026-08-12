---
title: "System::Xml::XmlWriterSettings class"
linktitle: "XmlWriterSettings"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlWriterSettings class. Especifica un conjunto de características para admitir en el objeto XmlWriter creado por el método XmlWriter::Create en C++."
type: docs
weight: 4500
url: /es/cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


Especifica un conjunto de características para admitir en el objeto [XmlWriter](../xmlwriter/) creado por el método [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Crea una copia de la instancia [XmlWriterSettings](./). |
| [get_CheckCharacters](./get_checkcharacters/)() | Devuelve un valor que indica si el escritor XML debe comprobar que todos los caracteres del documento cumplen con la sección "2.2 Characters" de la [Recomendación XML 1.0](https://www.w3.org/TR/REC-xml/#charsets) de la W3C. |
| [get_CloseOutput](./get_closeoutput/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) también debe cerrar el flujo subyacente o TextWriter cuando se llama al método [XmlWriter::Close](../xmlwriter/close/). |
| [get_ConformanceLevel](./get_conformancelevel/)() | Devuelve el nivel de conformidad que el escritor XML verifica en la salida XML. |
| [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) no escapa los atributos URI. |
| [get_Encoding](./get_encoding/)() | Devuelve el tipo de codificación de texto a usar. |
| [get_Indent](./get_indent/)() | Devuelve un valor que indica si se deben sangrar los elementos. |
| [get_IndentChars](./get_indentchars/)() | Devuelve la cadena de caracteres a usar al sangrar. Esta configuración se utiliza cuando el valor [XmlWriterSettings::set_Indent](./set_indent/) está establecido en **true**. |
| [get_NamespaceHandling](./get_namespacehandling/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) debe eliminar declaraciones de espacio de nombres duplicadas al escribir contenido XML. El comportamiento predeterminado es que el escritor emita todas las declaraciones de espacio de nombres que están presentes en el resolvedor de espacios de nombres del escritor. |
| [get_NewLineChars](./get_newlinechars/)() | Devuelve la cadena de caracteres a usar para los saltos de línea. |
| [get_NewLineHandling](./get_newlinehandling/)() | Devuelve un valor que indica si se deben normalizar los saltos de línea en la salida. |
| [get_NewLineOnAttributes](./get_newlineonattributes/)() | Devuelve un valor que indica si se deben escribir los atributos en una nueva línea. |
| [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Devuelve un valor que indica si se debe omitir una declaración XML. |
| [get_OutputMethod](./get_outputmethod/)() | Devuelve el método utilizado para serializar la salida del [XmlWriter](../xmlwriter/). |
| [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Devuelve un valor que indica si el [XmlWriter](../xmlwriter/) añadirá etiquetas de cierre a todas las etiquetas de elemento sin cerrar cuando se llame al método [XmlWriter::Close](../xmlwriter/close/). |
| [Reset](./reset/)() | Restablece los miembros de la clase de configuración a sus valores predeterminados. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Establece un valor que indica si el escritor XML debe comprobar que todos los caracteres del documento cumplen con la sección "2.2 Characters" de la [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) de W3C. |
| [set_CloseOutput](./set_closeoutput/)(bool) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) también debe cerrar el flujo subyacente o TextWriter cuando se llame al método [XmlWriter::Close](../xmlwriter/close/). |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Establece el nivel de conformidad que el escritor XML verifica en la salida XML. |
| [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(bool) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) no escapa los atributos URI. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Establece el tipo de codificación de texto a usar. |
| [set_Indent](./set_indent/)(bool) | Establece un valor que indica si se deben sangrar los elementos. |
| [set_IndentChars](./set_indentchars/)(const String\&) | Establece la cadena de caracteres a usar al sangrar. Esta configuración se utiliza cuando el valor de [XmlWriterSettings::set_Indent](./set_indent/) está establecido en **true**. |
| [set_NamespaceHandling](./set_namespacehandling/)(System::Xml::NamespaceHandling) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) debe eliminar declaraciones de espacio de nombres duplicadas al escribir contenido XML. El comportamiento predeterminado es que el escritor emita todas las declaraciones de espacio de nombres presentes en el resolvedor de espacios de nombres del escritor. |
| [set_NewLineChars](./set_newlinechars/)(const String\&) | Establece la cadena de caracteres a usar para los saltos de línea. |
| [set_NewLineHandling](./set_newlinehandling/)(System::Xml::NewLineHandling) | Establece un valor que indica si se deben normalizar los saltos de línea en la salida. |
| [set_NewLineOnAttributes](./set_newlineonattributes/)(bool) | Establece un valor que indica si se deben escribir los atributos en una nueva línea. |
| [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(bool) | Establece un valor que indica si se debe omitir una declaración XML. |
| [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(bool) | Establece un valor que indica si el [XmlWriter](../xmlwriter/) añadirá etiquetas de cierre a todas las etiquetas de elemento sin cerrar cuando se llame al método [XmlWriter::Close](../xmlwriter/close/). |
| [XmlWriterSettings](./xmlwritersettings/)() | Inicializa una nueva instancia de la clase [XmlWriterSettings](./). |
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
