---
title: "System::Xml::XmlReader::get_LocalName‑metod"
linktitle: "get_LocalName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::get_LocalName‑metod. När den åsidosätts i en avledd klass hämtar den det lokala namnet för den aktuella noden i C++."
type: docs
weight: 1400
url: /sv/cpp/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName method


När den åsidosätts i en avledd klass, hämtar den det lokala namnet på den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### ReturnValue

Namnet på den aktuella noden med prefixet borttaget. Till exempel är **LocalName** **book** för elementet **<bk:book>**. För nodtyper som inte har ett namn (som **[Text](../../../system.text/)**, **Comment** osv.) returnerar denna metod [String::Empty](../../../system/string/empty/).

## Se även

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
