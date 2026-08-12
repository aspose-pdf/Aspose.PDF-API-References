---
title: "Método System::Xml::XmlReader::Create"
linktitle: "Crear"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlReader::Create. Crea una nueva instancia de XmlReader usando el flujo especificado con la configuración predeterminada en C++."
type: docs
weight: 7700
url: /es/cpp/system.xml/xmlreader/create/
---
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method


Crea una nueva instancia de [XmlReader](../) usando el flujo especificado con la configuración predeterminada.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, se utiliza para continuar leyendo el flujo, y el procesamiento sigue analizando la entrada como un flujo de caracteres (Unicode). |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Crea una nueva instancia de [XmlReader](../) con el flujo y la configuración especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, se utiliza para continuar leyendo el flujo, y el procesamiento sigue analizando la entrada como un flujo de caracteres (Unicode). |
| settings | const SharedPtr\<XmlReaderSettings\>\& | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Crea una nueva instancia de [XmlReader](../) usando el flujo, la configuración y la información de contexto especificados para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, se utiliza para continuar leyendo el flujo, y el procesamiento sigue analizando la entrada como un flujo de caracteres (Unicode). |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, la codificación, el ámbito de espacio de nombres, el ámbito actual de **xml:lang** y **xml:space**, la URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Crea una nueva instancia de [XmlReader](../) usando el flujo, la URI base y la configuración especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | El flujo que contiene los datos XML. El [XmlReader](../) escanea los primeros bytes del flujo en busca de una marca de orden de bytes u otro indicio de codificación. Cuando se determina la codificación, se utiliza para continuar leyendo el flujo, y el procesamiento sigue analizando la entrada como un flujo de caracteres (Unicode). |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |
| baseUri | const String\& | La URI base para la entidad o documento que se está leyendo. Este valor puede ser **nullptr**. **[Security](../../../system.security/) Nota** La URI base se utiliza para resolver la URI relativa del documento XML. No use una URI base de una fuente no confiable. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method


Crea una nueva instancia de [XmlReader](../) utilizando el lector de texto especificado.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El lector de texto desde el cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Crea una nueva instancia de [XmlReader](../) utilizando el lector de texto y la configuración especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El lector de texto desde el cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | La configuración para la nueva [XmlReader](../). Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Crea una nueva instancia de [XmlReader](../) utilizando el lector de texto, la configuración y la información de contexto especificados para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El lector de texto desde el cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el lector XML para decodificar el flujo de datos. |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, la codificación, el ámbito de espacio de nombres, el ámbito actual de **xml:lang** y **xml:space**, la URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Crea una nueva instancia de [XmlReader](../) utilizando el lector de texto, la configuración y la URI base especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | El lector de texto desde el cual leer los datos XML. Un lector de texto devuelve un flujo de caracteres Unicode, por lo que la codificación especificada en la declaración XML no es utilizada por el [XmlReader](../) para decodificar el flujo de datos. |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |
| baseUri | const String\& | La URI base para la entidad o documento que se está leyendo. Este valor puede ser **nullptr**. **[Security](../../../system.security/) Nota** La URI base se utiliza para resolver la URI relativa del documento XML. No use una URI base de una fuente no confiable. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method


Crea una nueva instancia de [XmlReader](../) utilizando el lector XML y la configuración especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lector | const SharedPtr\<XmlReader\>\& | El objeto que desea usar como el lector XML subyacente. |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). El nivel de conformidad del objeto [XmlReaderSettings](../../xmlreadersettings/) debe coincidir con el nivel de conformidad del lector subyacente, o debe establecerse en [ConformanceLevel::Auto](../../conformancelevel/). |

### ReturnValue

Un objeto que envuelve al objeto [XmlReader](../) especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&) method


Crea una nueva instancia de [XmlReader](../) con la URI especificada.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | La URI del archivo que contiene los datos XML. La clase [XmlUrlResolver](../../xmlurlresolver/) se utiliza para convertir la ruta a una representación de datos canónica. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method


Crea una nueva instancia de [XmlReader](../) utilizando la URI y la configuración especificadas.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | El URI del archivo que contiene los datos XML. El objeto [XmlResolver](../../xmlresolver/) en el objeto [XmlReaderSettings](../../xmlreadersettings/) se utiliza para convertir la ruta a una representación de datos canónica. Si el valor XmlReaderSettings::get_XmlResolver es **nullptr**, se utiliza un nuevo objeto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const SharedPtr\<XmlReaderSettings\>\& | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Crea una nueva instancia de [XmlReader](../) usando el URI especificado, la configuración y la información de contexto para el análisis.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputUri | const String\& | El URI del archivo que contiene los datos XML. El objeto [XmlResolver](../../xmlresolver/) en el objeto [XmlReaderSettings](../../xmlreadersettings/) se utiliza para convertir la ruta a una representación de datos canónica. Si el valor XmlReaderSettings::get_XmlResolver es **nullptr**, se utiliza un nuevo objeto [XmlUrlResolver](../../xmlurlresolver/). |
| settings | SharedPtr\<XmlReaderSettings\> | La configuración para la nueva instancia de [XmlReader](../). Este valor puede ser **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | La información de contexto requerida para analizar el fragmento XML. La información de contexto puede incluir el [XmlNameTable](../../xmlnametable/) a usar, la codificación, el ámbito de espacio de nombres, el ámbito actual de **xml:lang** y **xml:space**, la URI base y la definición de tipo de documento. Este valor puede ser **nullptr**. |

### ReturnValue

Un objeto que se utiliza para leer los datos XML en el flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
