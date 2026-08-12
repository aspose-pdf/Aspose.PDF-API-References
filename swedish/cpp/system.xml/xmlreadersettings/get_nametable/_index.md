---
title: "System::Xml::XmlReaderSettings::get_NameTable-metoden"
linktitle: "get_NameTable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReaderSettings::get_NameTable-metoden. Returnerar XmlNameTable som används för atomiserade strängjämförelser i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable method


Returnerar den [XmlNameTable](../../xmlnametable/) som används för atomiserade strängjämförelser.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ReturnValue

Den [XmlNameTable](../../xmlnametable/) som lagrar alla atomiserade strängar som används av alla [XmlReader](../../xmlreader/)-instanser som skapats med detta [XmlReaderSettings](../)-objekt. Standardvärdet är **nullptr**. Den skapade [XmlReader](../../xmlreader/)-instansen kommer att använda en ny tom [NameTable](../../nametable/) om detta värde är **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
