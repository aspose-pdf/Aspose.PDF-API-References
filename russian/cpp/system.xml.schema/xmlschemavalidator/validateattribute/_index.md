---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateAttribute method"
linktitle: "ValidateAttribute"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateAttribute method. Проверяет имя атрибута, URI пространства имён и значение в текущем контексте элемента в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Проверяет имя атрибута, URI пространства имён и значение в контексте текущего элемента.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя атрибута для проверки. |
| namespaceUri | const String\& | URI пространства имён атрибута для проверки. |
| attributeValue | const String\& | Значение атрибута для проверки. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются после успешной проверки атрибута. Этот параметр может быть **nullptr**. |

### ReturnValue

Значение проверенного атрибута.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Проверяет имя атрибута, URI пространства имён и значение в контексте текущего элемента.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя атрибута для проверки. |
| namespaceUri | const String\& | URI пространства имён атрибута для проверки. |
| attributeValue | XmlValueGetter | Обратный вызов [XmlValueGetter](../../xmlvaluegetter/), используемый для передачи значения атрибута в виде типа, совместимого с типом XML [Schema](../../) Definition Language (XSD) атрибута. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются после успешной проверки атрибута. Этот параметр может быть **nullptr**. |

### ReturnValue

Значение проверенного атрибута.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
