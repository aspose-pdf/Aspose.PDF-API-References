---
title: "System::Xml::Schema::XmlSchemaType::IsDerivedFrom‑metod"
linktitle: "IsDerivedFrom"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaType::IsDerivedFrom‑metod. Returnerar ett värde som indikerar om den angivna härledda schematypen är härledd från den angivna baskschematypen i C++."
type: docs
weight: 1700
url: /sv/cpp/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom method


Returnerar ett värde som indikerar om den specificerade avledda schematypen är avledd från den specificerade bas‑schematypen.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| derivedType | SharedPtr\<XmlSchemaType\> | Den härledda [XmlSchemaType](../) att testa. |
| baseType | const SharedPtr\<XmlSchemaType\>\& | Den bas [XmlSchemaType](../) att testa den härledda [XmlSchemaType](../) mot. |
| except | XmlSchemaDerivationMethod | Ett av [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)-värdena som representerar en typderiveringsmetod att utesluta från testning. |

### ReturnValue

**true** if the derived type is derived from the base type; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
