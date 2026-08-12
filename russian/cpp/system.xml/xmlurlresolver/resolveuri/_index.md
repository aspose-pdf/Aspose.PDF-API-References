---
title: "System::Xml::XmlUrlResolver::ResolveUri метод"
linktitle: "ResolveUri"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlUrlResolver::ResolveUri метод. Определяет абсолютный URI из базового и относительного URI в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri method


Разрешает абсолютный URI из базового и относительного URI.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | String | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение эффективно заменяет значение **baseUri**. Если относительный, оно комбинируется с **baseUri**, чтобы получить абсолютный URI. |

### ReturnValue

Абсолютный URI или **nullptr**, если относительный URI не может быть разрешён.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
