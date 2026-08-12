---
title: "Método System::Xml::Schema::XmlSchemaType::IsDerivedFrom"
linktitle: "IsDerivedFrom"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Schema::XmlSchemaType::IsDerivedFrom. Devuelve un valor que indica si el tipo de esquema derivado especificado se deriva del tipo de esquema base especificado en C++."
type: docs
weight: 1700
url: /es/cpp/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom method


Devuelve un valor que indica si el tipo de esquema derivado especificado se deriva del tipo de esquema base especificado.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| derivedType | SharedPtr\<XmlSchemaType\> | El [XmlSchemaType](../) derivado a probar. |
| baseType | const SharedPtr\<XmlSchemaType\>\& | El [XmlSchemaType](../) base contra el cual probar el [XmlSchemaType](../) derivado. |
| except | XmlSchemaDerivationMethod | Uno de los valores de [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) que representa un método de derivación de tipo a excluir de la prueba. |

### ReturnValue

**true** if the derived type is derived from the base type; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
