---
title: "System::Xml::XmlUrlResolver::GetEntity метод"
linktitle: "GetEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlUrlResolver::GetEntity метод. Преобразует URI в объект, содержащий фактический ресурс в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity method


Отображает URI на объект, содержащий фактический ресурс.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI, возвращаемый вызовом [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| роль | String | В настоящее время не используется. |
| ofObjectToReturn | const TypeInfo\& | Тип возвращаемого объекта. Текущая реализация возвращает только объекты Stream. |

### ReturnValue

Объект потока или **nullptr**, если указан тип, отличный от потока.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
