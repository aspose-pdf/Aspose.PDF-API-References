---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement método"
linktitle: "ValidateEndElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement método. Verifica si el contenido de texto del elemento es válido según su tipo de datos para elementos con contenido simple, y verifica si el contenido del elemento actual está completo para elementos con contenido complejo en C++."
type: docs
weight: 1800
url: /es/cpp/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


Verifica si el contenido de texto del elemento es válido según su tipo de datos para elementos con contenido simple, y verifica si el contenido del elemento actual está completo para elementos con contenido complejo.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras una validación exitosa del elemento. Este parámetro puede ser **nullptr**. |

### ReturnValue

El valor de texto analizado y tipado del elemento si el elemento tiene contenido simple.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


Verifica si el contenido de texto del elemento especificado es válido según su tipo de datos.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras una validación exitosa del contenido de texto del elemento. Este parámetro puede ser **nullptr**. |
| typedValue | const SharedPtr\<Object\>\& | El contenido de texto tipado del elemento. |

### ReturnValue

El contenido simple analizado y tipado del elemento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
