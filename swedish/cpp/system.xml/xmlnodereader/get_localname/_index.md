---
title: "System::Xml::XmlNodeReader::get_LocalName metod"
linktitle: "get_LocalName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeReader::get_LocalName metod. Returnerar det lokala namnet på den aktuella noden i C++."
type: docs
weight: 1300
url: /sv/cpp/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName method


Returnerar det lokala namnet på den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### ReturnValue

Namnet på den aktuella noden med prefixet borttaget. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment** osv.) returnerar denna metod [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
