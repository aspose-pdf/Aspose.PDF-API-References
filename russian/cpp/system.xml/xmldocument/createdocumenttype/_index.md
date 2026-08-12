---
title: "System::Xml::XmlDocument::CreateDocumentType метод"
linktitle: "CreateDocumentType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocument::CreateDocumentType метод. Возвращает новый объект XmlDocumentType в C++."
type: docs
weight: 700
url: /ru/cpp/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType method


Возвращает новый объект [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | const String\& | Имя типа документа. |
| publicId | const String\& | Публичный идентификатор типа документа или **nullptr**. Вы можете указать публичный URI, а также системный идентификатор для определения местоположения внешнего подмножества DTD. |
| systemId | const String\& | Системный идентификатор типа документа или **nullptr**. Указывает URL расположения файла внешнего подмножества DTD. |
| internalSubset | const String\& | Внутреннее подмножество DTD типа документа или **nullptr**. |

### ReturnValue

Новый [XmlDocumentType](../../xmldocumenttype/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
