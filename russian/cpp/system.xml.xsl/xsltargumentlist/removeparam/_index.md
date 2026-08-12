---
title: "Метод System::Xml::Xsl::XsltArgumentList::RemoveParam"
linktitle: "RemoveParam"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Xsl::XsltArgumentList::RemoveParam. Удаляет параметр из XsltArgumentList в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam method


Удаляет параметр из [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const String\& | Имя удаляемого параметра. [XsltArgumentList](../) не проверяет, является ли переданное имя допустимым локальным именем; однако имя не может быть **nullptr**. |
| namespaceUri | const String\& | URI пространства имён параметра, который нужно удалить. |

### ReturnValue

Объект параметра или **nullptr**, если он не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
