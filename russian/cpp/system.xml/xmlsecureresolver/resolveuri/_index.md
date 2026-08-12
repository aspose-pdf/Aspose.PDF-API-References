---
title: "System::Xml::XmlSecureResolver::ResolveUri метод"
linktitle: "ResolveUri"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlSecureResolver::ResolveUri метод. Определяет абсолютный URI из базового и относительного URI, вызывая ResolveUri у базового XmlResolver в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri method


Определяет абсолютный URI из базового и относительного URI, вызывая **ResolveUri** у базового [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | String | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение эффективно заменяет значение **baseUri**. Если относительный, оно комбинируется с **baseUri**, чтобы получить абсолютный URI. |

### ReturnValue

Абсолютный URI или **nullptr**, если относительный URI нельзя разрешить (возвращается при вызове **ResolveUri** у базового [XmlResolver](../../xmlresolver/)).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
