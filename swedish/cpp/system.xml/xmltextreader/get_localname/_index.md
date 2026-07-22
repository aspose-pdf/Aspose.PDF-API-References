---
title: "System::Xml::XmlTextReader::get_LocalName metod"
linktitle: "get_LocalName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::get_LocalName metod. Returnerar det lokala namnet på den aktuella noden i C++."
type: docs
weight: 1800
url: /sv/cpp/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName method


Returnerar det lokala namnet på den aktuella noden.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### ReturnValue

Namnet på den aktuella noden med prefixet borttaget. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment** osv.) returnerar denna metod [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
