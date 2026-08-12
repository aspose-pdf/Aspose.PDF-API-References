---
title: "System::Xml::XmlTextReader::get_LocalName method"
linktitle: "get_LocalName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlTextReader::get_LocalName method. Devuelve el nombre local del nodo actual en C++."
type: docs
weight: 1800
url: /es/cpp/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName method


Devuelve el nombre local del nodo actual.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### ReturnValue

El nombre del nodo actual sin el prefijo. Por ejemplo, **LocalName** es **book** para el elemento **<bk:book>**. Para los tipos de nodo que no tienen nombre (como **[Text](../../../system.text/)**, **Comment**, etc.), este método devuelve [String::Empty](../../../system/string/empty/).

## Ver también

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
