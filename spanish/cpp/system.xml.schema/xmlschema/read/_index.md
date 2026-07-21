---
title: "System::Xml::Schema::XmlSchema::Read método"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchema::Read método. Lee un esquema XML desde el flujo suministrado en C++."
type: docs
weight: 2900
url: /es/cpp/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method


Lee un [Schema](../../) XML desde el flujo suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<IO::Stream\>\& | El flujo de datos proporcionado. |
| validationEventHandler | ValidationEventHandler | El controlador de eventos de validación que recibe información sobre errores de sintaxis del [Schema](../../) XML. |

### ReturnValue

El objeto [XmlSchema](../) que representa el [Schema](../../) XML.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [Stream](../../../system.io/stream/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method


Lee un [Schema](../../) XML desde el [IO::TextReader](../../../system.io/textreader/) suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const SharedPtr\<IO::TextReader\>\& | El [IO::TextReader](../../../system.io/textreader/) que contiene el [Schema](../../) XML a leer. |
| validationEventHandler | ValidationEventHandler | El controlador de eventos de validación que recibe información sobre los errores de sintaxis del [Schema](../../) XML. |

### ReturnValue

El objeto [XmlSchema](../) que representa el [Schema](../../) XML.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method


Lee un [Schema](../../) XML desde el [XmlReader](../../../system.xml/xmlreader/) suministrado.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene el [Schema](../../) XML a leer. |
| validationEventHandler | ValidationEventHandler | El controlador de eventos de validación que recibe información sobre los errores de sintaxis del [Schema](../../) XML. |

### ReturnValue

El objeto [XmlSchema](../) que representa el [Schema](../../) XML.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
