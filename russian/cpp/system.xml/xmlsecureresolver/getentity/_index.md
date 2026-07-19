---
title: "System::Xml::XmlSecureResolver::GetEntity method"
linktitle: "GetEntity"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlSecureResolver::GetEntity method. Сопоставляет URI с объектом, содержащим реальный ресурс в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity method


Отображает URI на объект, содержащий фактический ресурс.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | SharedPtr\<Uri\> | URI, возвращаемый вызовом [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| роль | String | В настоящее время не используется. |
| ofObjectToReturn | const TypeInfo\& | Тип возвращаемого объекта. Текущая версия возвращает только объекты Stream. |

### ReturnValue

Поток, возвращаемый вызовом **GetEntity** у базового [XmlResolver](../../xmlresolver/). Если указан тип, отличный от Stream, метод возвращает **nullptr**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
