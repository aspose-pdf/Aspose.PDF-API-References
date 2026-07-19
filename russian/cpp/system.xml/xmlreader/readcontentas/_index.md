---
title: "System::Xml::XmlReader::ReadContentAs method"
linktitle: "ReadContentAs"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlReader::ReadContentAs method. Считывает содержимое как объект указанного типа в C++."
type: docs
weight: 3900
url: /ru/cpp/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs method


Считывает содержимое как объект указанного типа.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| returnType | const TypeInfo\& | Тип возвращаемого значения. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), используемый для разрешения любых префиксов пространств имён, связанных с преобразованием типов. Например, его можно использовать при преобразовании объекта [XmlQualifiedName](../../xmlqualifiedname/) в **xs:string**. Это значение может быть **nullptr**. |

### ReturnValue

Объединённое текстовое содержимое или значение атрибута, преобразованное в запрошенный тип.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
