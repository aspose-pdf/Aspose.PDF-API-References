---
title: "System::Xml::XmlResolver::SupportsType method"
linktitle: "SupportsType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlResolver::SupportsType method. Позволяет разрешителю возвращать типы, отличные от Stream, в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType method


Позволяет разрешателю возвращать типы, отличные от Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI. |
| тип | const TypeInfo\& | Тип для возврата. |

### ReturnValue

**true** if the **type** is supported; otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
