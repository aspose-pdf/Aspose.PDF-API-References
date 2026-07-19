---
title: "Метод System::Xml::XPath::XPathNavigator::CheckValidity"
linktitle: "CheckValidity"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::XPath::XPathNavigator::CheckValidity. Проверяет, что XML‑данные в XPathNavigator соответствуют схеме языка определения XML Schema (XSD), предоставленной в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity method


Проверяет, что XML‑данные в [XPathNavigator](../) соответствуют схеме языка определения XML [Schema](../../../system.xml.schema/) (XSD), предоставленной.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| schemas | SharedPtr\<System::Xml::Schema::XmlSchemaSet\> | Набор XmlSchemaSet, содержащий схемы, используемые для проверки XML‑данных, содержащихся в [XPathNavigator](../). |
| validationEventHandler | System::Xml::Schema::ValidationEventHandler | Объект ValidationEventHandler, получающий информацию о предупреждениях и ошибках проверки схемы. |

### ReturnValue

**true** if no schema validation errors occurred; otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
