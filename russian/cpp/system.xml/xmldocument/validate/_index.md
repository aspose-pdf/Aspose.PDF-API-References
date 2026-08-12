---
title: "System::Xml::XmlDocument::Validate метод"
linktitle: "Валидация"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocument::Validate метод. Выполняет проверку XmlDocument против схем XML Schema Definition Language (XSD), содержащихся в списке XmlDocument::get_Schemas, в C++."
type: docs
weight: 4300
url: /ru/cpp/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) method


Проверяет [XmlDocument](../) против схем XML [Schema](../../../system.xml.schema/) Definition Language (XSD), содержащихся в списке [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | Объект [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), получающий информацию о предупреждениях и ошибках проверки схем. |

## См. также

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) method


Проверяет указанный объект [XmlNode](../../xmlnode/) против схем XML [Schema](../../../system.xml.schema/) Definition Language (XSD), находящихся в списке [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | Объект [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), получающий информацию о предупреждениях и ошибках проверки схем. |
| nodeToValidate | const SharedPtr\<XmlNode\>\& | Объект [XmlNode](../../xmlnode/), созданный из [XmlDocument](../) для проверки. |

## См. также

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
