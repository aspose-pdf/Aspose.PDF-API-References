---
title: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes método"
linktitle: "GetUnspecifiedDefaultAttributes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes método. Valida las restricciones de identidad sobre los atributos predeterminados y rellena la List especificada con objetos XmlSchemaAttribute para cualquier atributo con valores predeterminados que no haya sido previamente validado usando el método XmlSchemaValidator::ValidateAttribute en el contexto de elemento en C++."
type: docs
weight: 900
url: /es/cpp/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes method


Valida las restricciones de identidad sobre los atributos predeterminados y rellena la List especificada con objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para cualquier atributo con valores predeterminados que no haya sido previamente validado usando el método [XmlSchemaValidator::ValidateAttribute](../validateattribute/) en el contexto de elemento.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| defaultAttributes | const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\& | Una List para rellenar con objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para cualquier atributo que aún no se haya encontrado durante la validación en el contexto de elemento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
