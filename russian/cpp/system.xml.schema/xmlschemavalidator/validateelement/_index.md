---
title: "Метод System::Xml::Schema::XmlSchemaValidator::ValidateElement"
linktitle: "ValidateElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Xml::Schema::XmlSchemaValidator::ValidateElement. Проверяет элемент в текущем контексте в C++."
type: docs
weight: 1700
url: /ru/cpp/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Проверяет элемент в текущем контексте.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя элемента для проверки. |
| namespaceUri | const String\& | URI пространства имён элемента для проверки. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке имени элемента. Этот параметр может быть **nullptr**. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method


Проверяет элемент в текущем контексте с указанными значениями атрибутов **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** и **xsi:NoNamespaceSchemaLocation**.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | const String\& | Локальное имя элемента для проверки. |
| namespaceUri | const String\& | URI пространства имён элемента для проверки. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Объект [XmlSchemaInfo](../../xmlschemainfo/), свойства которого устанавливаются при успешной проверке имени элемента. Этот параметр может быть **nullptr**. |
| xsiType | const String\& | Значение атрибута **xsi:Type** элемента. Этот параметр может быть **nullptr**. |
| xsiNil | const String\& | Значение атрибута **xsi:Nil** элемента. Этот параметр может быть **nullptr**. |
| xsiSchemaLocation | const String\& | Значение атрибута **xsi:SchemaLocation** элемента. Этот параметр может быть **nullptr**. |
| xsiNoNamespaceSchemaLocation | const String\& | Значение атрибута **xsi:NoNamespaceSchemaLocation** элемента. Этот параметр может быть **nullptr**. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
