---
title: "System::Xml::Schema::XmlSchemaDatatype::ChangeType метод"
linktitle: "ChangeType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaDatatype::ChangeType метод. Преобразует указанное значение, тип которого является одной из допустимых репрезентаций XML‑схемы, представленной XmlSchemaDatatype, в тип выполнения, указанный в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Преобразует указанное значение, тип которого является одной из допустимых репрезентаций XML‑схемы, представленной [XmlSchemaDatatype](../), в указанный тип выполнения.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | SharedPtr\<Object\> | Входное значение для преобразования в указанный тип. |
| targetType | const TypeInfo\& | Целевой тип, в который нужно преобразовать входное значение. |

### ReturnValue

Преобразованное входное значение.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа схемы XML, представленного [XmlSchemaDatatype](../), в тип выполнения, указанный с помощью [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), если [XmlSchemaDatatype](../) представляет тип **xs:QName** или тип, производный от него.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | SharedPtr\<Object\> | Входное значение для преобразования в указанный тип. |
| targetType | const TypeInfo\& | Целевой тип, в который нужно преобразовать входное значение. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. Полезен только в том случае, если [XmlSchemaDatatype](../) представляет тип **xs:QName** или тип, производный от него. |

### ReturnValue

Преобразованное входное значение.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
