---
title: "Метод System::Xml::Xsl::XsltArgumentList::GetParam"
linktitle: "GetParam"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::XsltArgumentList::GetParam. Возвращает параметр, связанный с именем, квалифицированным пространством имён, в C++."
type: docs
weight: 600
url: /ru/cpp/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam method


Возвращает параметр, связанный с квалифицированным именем пространства имён.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const String\& | Имя параметра. [XsltArgumentList](../) не проверяет, является ли переданное имя допустимым локальным именем; однако имя не может быть **nullptr**. |
| namespaceUri | const String\& | URI пространства имён, связанное с параметром. |

### ReturnValue

Объект параметра или **nullptr**, если он не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
