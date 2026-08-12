---
title: "Constructor System::Xml::XmlTextWriter::XmlTextWriter"
linktitle: "XmlTextWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::Xml::XmlTextWriter::XmlTextWriter. Crea una instancia de la clase XmlTextWriter usando el flujo y la codificación especificados en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) usando el flujo y la codificación especificados.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | El flujo al que desea escribir. |
| encoding | const SharedPtr\<Text::Encoding\>\& | La codificación a generar. Si la codificación es **nullptr** escribe el flujo como UTF-8 y omite el atributo de codificación del **ProcessingInstruction**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) usando el TextWriter especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | El TextWriter al que escribir. Se asume que el TextWriter ya está configurado con la codificación correcta. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Crea una instancia de la clase [XmlTextWriter](../) usando el archivo especificado.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | El nombre de archivo al que escribir. Si el archivo existe, lo trunca y lo sobrescribe con el nuevo contenido. |
| encoding | const SharedPtr\<Text::Encoding\>\& | La codificación a generar. Si la codificación es **nullptr** escribe el archivo como UTF-8 y omite el atributo de codificación del **ProcessingInstruction**. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
