---
title: System::Xml::XmlReaderSettings::get_NameTable method
linktitle: get_NameTable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReaderSettings::get_NameTable method. Returns the XmlNameTable used for atomized string comparisons in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable method


Returns the [XmlNameTable](../../xmlnametable/) used for atomized string comparisons.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### ReturnValue

The [XmlNameTable](../../xmlnametable/) that stores all the atomized strings used by all [XmlReader](../../xmlreader/) instances created using this [XmlReaderSettings](../) object. The default is **nullptr**. The created [XmlReader](../../xmlreader/) instance will use a new empty [NameTable](../../nametable/) if this value is **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
