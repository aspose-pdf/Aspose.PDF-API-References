---
title: "System::Xml::Schema::XmlSchemaInference::InferSchema метод"
linktitle: "InferSchema"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaInference::InferSchema метод. Выводит схему XML Schema Definition Language (XSD) из XML‑документа, содержащегося в объекте XmlReader, указанном в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


Выводит схему XML [Schema](../../) Definition Language (XSD) из XML‑документа, содержащегося в объекте [XmlReader](../../../system.xml/xmlreader/) .

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/) , содержащий XML‑документ, из которого будет выводиться схема. |

### ReturnValue

Объект [XmlSchemaSet](../../xmlschemaset/) , содержащий выведенные схемы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


Выводит схему XML [Schema](../../) Definition Language (XSD) из XML‑документа, содержащегося в указанном объекте [XmlReader](../../../system.xml/xmlreader/), и уточняет полученную схему, используя существующую схему в указанном объекте [XmlSchemaSet](../../xmlschemaset/) с тем же целевым пространством имён.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Объект [XmlReader](../../../system.xml/xmlreader/) , содержащий XML‑документ, из которого будет выводиться схема. |
| schemas | SharedPtr\<XmlSchemaSet\> | Объект [XmlSchemaSet](../../xmlschemaset/) , содержащий существующую схему, используемую для уточнения выведенной схемы. |

### ReturnValue

Объект [XmlSchemaSet](../../xmlschemaset/) , содержащий выведенные схемы.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
