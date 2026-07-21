---
title: "Aspose::Pdf::Document::BindXml método"
linktitle: "BindXml"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::BindXml método. Vincula xml al documento en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/document/bindxml/
---
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&) method


Vincula xml al documento.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &stream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const System::SharedPtr\<System::IO::Stream\>\& | El flujo xml. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Vincula xml/xsl al documento.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &xmlStream, const System::SharedPtr<System::IO::Stream> &xslStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo xml. |
| xslStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo xsl si se usa XSLT. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Xml::XmlReaderSettings\>\&) method


Vincula xml/xsl al documento.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &xmlStream, const System::SharedPtr<System::IO::Stream> &xslStream, const System::SharedPtr<System::Xml::XmlReaderSettings> &settings)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo xml. |
| xslStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo xsl si se usa XSLT. |
| settings | const System::SharedPtr\<System::Xml::XmlReaderSettings\>\& | La configuración del lector xml. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../../system.xml/xmlreadersettings/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::String\&, const System::String\&) method


Vincula xml/xsl al documento.

```cpp
void Aspose::Pdf::Document::BindXml(const System::String &xmlFile, const System::String &xslFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlFile | const System::String\& | El archivo xml. |
| xslFile | const System::String\& | El archivo xsl si se usa XSLT. |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(System::String) method


Vincula xml al documento.

```cpp
void Aspose::Pdf::Document::BindXml(System::String file)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | System::String | El archivo xml |

## Ver también

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
