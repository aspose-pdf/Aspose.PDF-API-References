---
title: "Метод System::Xml::Resolvers::XmlPreloadedResolver::GetEntity"
linktitle: "GetEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Resolvers::XmlPreloadedResolver::GetEntity. Преобразует URI в объект, содержащий фактический ресурс в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity method


Отображает URI на объект, содержащий фактический ресурс.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI, возвращаемый вызовом [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| роль | String | В настоящее время не используется. |
| ofObjectToReturn | const TypeInfo\& | Тип возвращаемого объекта. [XmlPreloadedResolver](../) поддерживает объекты Stream и TextReader для URI, добавленных как [String](../../../system/string/). Если запрашиваемый тип не поддерживается разрешителем, будет выброшено исключение. Используйте метод XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo), чтобы определить, поддерживается ли определённый **Type** этим разрешителем. |

### ReturnValue

Объект Stream или TextReader, соответствующий фактическому источнику.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PDF for C++](../../../)
