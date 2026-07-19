---
title: "System::Xml::Schema::XmlSchemaType::IsDerivedFrom метод"
linktitle: "IsDerivedFrom"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaType::IsDerivedFrom метод. Возвращает значение, указывающее, является ли указанный производный тип схемы производным от указанного базового типа схемы в C++."
type: docs
weight: 1700
url: /ru/cpp/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom method


Возвращает значение, указывающее, является ли указанный производный тип схемы производным от указанного базового типа схемы.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| derivedType | SharedPtr\<XmlSchemaType\> | Производный [XmlSchemaType](../) для тестирования. |
| baseType | const SharedPtr\<XmlSchemaType\>\& | Базовый [XmlSchemaType](../) для проверки производного [XmlSchemaType](../). |
| except | XmlSchemaDerivationMethod | Одно из значений [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/), представляющих метод вывода типа, который следует исключить из тестирования. |

### ReturnValue

**true** if the derived type is derived from the base type; otherwise, **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
