---
title: "System::Xml::XmlTextReader::XmlTextReader constructor"
linktitle: "XmlTextReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::XmlTextReader constructor. Inicializa una nueva instancia de la clase XmlTextReader con el flujo especificado en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML a leer. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo especificado y [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML a leer. |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el flujo especificado, [XmlNodeType](../../xmlnodetype/) y [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | El flujo que contiene el fragmento XML a analizar. |
| fragType | XmlNodeType | El [XmlNodeType](../../xmlnodetype/) del fragmento XML. Esto también determina lo que el fragmento puede contener. |
| context | const SharedPtr\<XmlParserContext\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar el **xmlFragment**. Esto incluye la [XmlNameTable](../../xmlnametable/) a usar, la codificación, el ámbito de espacio de nombres, el **xml:lang** actual y el ámbito **xml:space**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el TextReader especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El TextReader que contiene los datos XML a leer. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el TextReader especificado y la [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El TextReader que contiene los datos XML a leer. |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el archivo especificado.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL del archivo que contiene los datos XML. La [XmlTextReader::get_BaseURI](../get_baseuri/) se establece en este valor. |

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL y el flujo especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL a usar para resolver recursos externos. La [XmlTextReader::get_BaseURI](../get_baseuri/) se establece en este valor. |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML a leer. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL, el flujo y la [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL a usar para resolver recursos externos. La [XmlTextReader::get_BaseURI](../get_baseuri/) se establece en este valor. Si **url** es **nullptr**, **BaseURI** se establece en [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML a leer. |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL y el TextReader especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL a usar para resolver recursos externos. La [XmlTextReader::get_BaseURI](../get_baseuri/) se establece en este valor. |
| input | const SharedPtr\<IO::TextReader\>\& | El TextReader que contiene los datos XML a leer. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con la URL, el TextReader y la [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL a usar para resolver recursos externos. La [XmlTextReader::get_BaseURI](../get_baseuri/) se establece en este valor. Si **url** es **nullptr**, **BaseURI** se establece en [String::Empty](../../../system/string/empty/). |
| input | const SharedPtr\<IO::TextReader\>\& | El TextReader que contiene los datos XML a leer. |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con el archivo y la [XmlNameTable](../../xmlnametable/) especificados.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | const String\& | La URL del archivo que contiene los datos XML a leer. |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Inicializa una nueva instancia de la clase [XmlTextReader](../) con la cadena especificada, el [XmlNodeType](../../xmlnodetype/) y el [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFragment | const String\& | La cadena que contiene el fragmento XML a analizar. |
| fragType | XmlNodeType | El [XmlNodeType](../../xmlnodetype/) del fragmento XML. Esto también determina lo que la cadena del fragmento puede contener. |
| context | const SharedPtr\<XmlParserContext\>\& | El [XmlParserContext](../../xmlparsercontext/) en el que se debe analizar el **xmlFragment**. Esto incluye la [XmlNameTable](../../xmlnametable/) a usar, la codificación, el ámbito de espacio de nombres, el **xml:lang** actual y el ámbito **xml:space**. |

## Ver también

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
