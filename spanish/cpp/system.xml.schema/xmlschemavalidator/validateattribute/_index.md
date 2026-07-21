---
title: "Método System::Xml::Schema::XmlSchemaValidator::ValidateAttribute"
linktitle: "ValidateAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Xml::Schema::XmlSchemaValidator::ValidateAttribute. Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del atributo a validar. |
| namespaceUri | const String\& | El URI del espacio de nombres del atributo a validar. |
| attributeValue | const String\& | El valor del atributo a validar. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del atributo. Este parámetro puede ser **nullptr**. |

### ReturnValue

El valor del atributo validado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Valida el nombre del atributo, el URI del espacio de nombres y el valor en el contexto del elemento actual.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del atributo a validar. |
| namespaceUri | const String\& | El URI del espacio de nombres del atributo a validar. |
| attributeValue | XmlValueGetter | Una devolución de llamada [XmlValueGetter](../../xmlvaluegetter/) usada para pasar el valor del atributo como un tipo compatible con el tipo del Lenguaje de Definición de Esquema (XSD) del [Schema](../../) XML del atributo. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del atributo. Este parámetro puede ser **nullptr**. |

### ReturnValue

El valor del atributo validado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
