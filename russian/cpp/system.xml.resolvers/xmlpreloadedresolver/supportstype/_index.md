---
title: "Метод System::Xml::Resolvers::XmlPreloadedResolver::SupportsType"
linktitle: "SupportsType"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Resolvers::XmlPreloadedResolver::SupportsType. Определяет, поддерживает ли разрешитель другие **Type**, кроме Stream, в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType method


Определяет, поддерживает ли резолвер другие типы, помимо Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | Абсолютный URI для проверки. |
| тип | const TypeInfo\& | Тип для возврата. |

### ReturnValue

**true** if the Type is supported; otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
