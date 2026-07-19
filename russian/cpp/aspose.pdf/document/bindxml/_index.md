---
title: "Aspose::Pdf::Document::BindXml method"
linktitle: "BindXml"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document::BindXml method. Привязывает XML к документу в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/document/bindxml/
---
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&) method


Привязать xml к документу.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &stream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | XML‑поток. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Привязать xml/xsl к документу.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &xmlStream, const System::SharedPtr<System::IO::Stream> &xslStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | const System::SharedPtr\<System::IO::Stream\>\& | XML‑поток. |
| xslStream | const System::SharedPtr\<System::IO::Stream\>\& | XSL‑поток, если используется XSLT. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Xml::XmlReaderSettings\>\&) method


Привязать xml/xsl к документу.

```cpp
void Aspose::Pdf::Document::BindXml(const System::SharedPtr<System::IO::Stream> &xmlStream, const System::SharedPtr<System::IO::Stream> &xslStream, const System::SharedPtr<System::Xml::XmlReaderSettings> &settings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlStream | const System::SharedPtr\<System::IO::Stream\>\& | XML‑поток. |
| xslStream | const System::SharedPtr\<System::IO::Stream\>\& | XSL‑поток, если используется XSLT. |
| настройки | const System::SharedPtr\<System::Xml::XmlReaderSettings\>\& | Настройки XML‑чтения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../../system.xml/xmlreadersettings/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(const System::String\&, const System::String\&) method


Привязать xml/xsl к документу.

```cpp
void Aspose::Pdf::Document::BindXml(const System::String &xmlFile, const System::String &xslFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | const System::String\& | XML‑файл. |
| xslFile | const System::String\& | XSL‑файл, если используется XSLT. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::BindXml(System::String) method


Привязать xml к документу.

```cpp
void Aspose::Pdf::Document::BindXml(System::String file)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| file | System::String | XML‑файл |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
