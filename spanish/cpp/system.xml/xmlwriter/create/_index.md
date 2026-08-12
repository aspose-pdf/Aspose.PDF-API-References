---
title: "Método System::Xml::XmlWriter::Create"
linktitle: "Crear"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::XmlWriter::Create. Crea una nueva instancia de XmlWriter usando el flujo especificado en C++."
type: docs
weight: 3700
url: /es/cpp/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method


Crea una nueva instancia de [XmlWriter](../) usando el flujo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al flujo especificado. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method


Crea una nueva instancia de [XmlWriter](../) usando el flujo y el objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | El flujo al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al flujo especificado. |
| settings | SharedPtr\<XmlWriterSettings\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia de [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está usando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method


Crea una nueva instancia de [XmlWriter](../) usando el TextWriter especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al TextWriter especificado. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Crea una nueva instancia de [XmlWriter](../) usando el TextWriter y los objetos [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que desea escribir. El [XmlWriter](../) escribe la sintaxis de texto XML 1.0 y lo agrega al TextWriter especificado. |
| settings | SharedPtr\<XmlWriterSettings\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia de [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está usando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method


Crea una nueva instancia de [XmlWriter](../) usando el [Text::StringBuilder](../../../system.text/stringbuilder/) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | El [Text::StringBuilder](../../../system.text/stringbuilder/) al que se debe escribir. El contenido escrito por el [XmlWriter](../) se agrega al [Text::StringBuilder](../../../system.text/stringbuilder/). |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method


Crea una nueva instancia de [XmlWriter](../) usando el [Text::StringBuilder](../../../system.text/stringbuilder/) y los objetos [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | El [Text::StringBuilder](../../../system.text/stringbuilder/) al que se debe escribir. El contenido escrito por el [XmlWriter](../) se agrega al [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | SharedPtr\<XmlWriterSettings\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia de [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está usando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method


Crea una nueva instancia de [XmlWriter](../) usando el objeto [XmlWriter](../) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | El objeto [XmlWriter](../) que desea usar como escritor subyacente. |

### ReturnValue

Un objeto [XmlWriter](../) que envuelve al objeto [XmlWriter](../) especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Crea una nueva instancia de [XmlWriter](../) usando los objetos [XmlWriter](../) y [XmlWriterSettings](../../xmlwritersettings/) especificados.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | El objeto [XmlWriter](../) que desea usar como escritor subyacente. |
| settings | SharedPtr\<XmlWriterSettings\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia de [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está usando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### ReturnValue

Un objeto [XmlWriter](../) que envuelve al objeto [XmlWriter](../) especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&) method


Crea una nueva instancia de [XmlWriter](../) usando el nombre de archivo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const String\& | El archivo al que desea escribir. El [XmlWriter](../) crea un archivo en la ruta especificada y escribe en él con la sintaxis de texto XML 1.0. El **outputFileName** debe ser una ruta del sistema de archivos. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method


Crea una nueva instancia de [XmlWriter](../) usando el nombre de archivo y el objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFileName | const String\& | El archivo al que desea escribir. El [XmlWriter](../) crea un archivo en la ruta especificada y escribe en él con la sintaxis de texto XML 1.0. El **outputFileName** debe ser una ruta del sistema de archivos. |
| settings | SharedPtr\<XmlWriterSettings\> | El objeto [XmlWriterSettings](../../xmlwritersettings/) utilizado para configurar la nueva instancia de [XmlWriter](../). Si es **nullptr**, se usa un [XmlWriterSettings](../../xmlwritersettings/) con la configuración predeterminada. Si el [XmlWriter](../) se está usando con el método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), debe usar el valor XslCompiledTransform::get_OutputSettings para obtener un objeto [XmlWriterSettings](../../xmlwritersettings/) con la configuración correcta. Esto garantiza que el objeto [XmlWriter](../) creado tenga la configuración de salida correcta. |

### ReturnValue

Un objeto [XmlWriter](../).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
