---
title: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor"
linktitle: "XmlSchemaValidator"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor. Инициализирует новый экземпляр класса XmlSchemaValidator в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator constructor


Инициализирует новый экземпляр класса [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nameTable | const SharedPtr\<XmlNameTable\>\& | Объект [XmlNameTable](../../../system.xml/xmlnametable/), содержащий имена элементов и атрибутов в виде атомизированных строк. |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | Объект [XmlSchemaSet](../../xmlschemaset/), содержащий схемы XML [Schema](../../) Definition Language (XSD), используемые для проверки. |
| namespaceResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения пространств имён, встречающихся во время проверки. |
| validationFlags | XmlSchemaValidationFlags | Значение [XmlSchemaValidationFlags](../../xmlschemavalidationflags/), определяющее параметры проверки схемы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
