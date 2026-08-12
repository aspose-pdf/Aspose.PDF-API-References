---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateElement method"
linktitle: "ValidateElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateElement method. Valida el elemento en el contexto actual en C++."
type: docs
weight: 1700
url: /es/cpp/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Valida el elemento en el contexto actual.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del elemento a validar. |
| namespaceUri | const String\& | El URI del espacio de nombres del elemento a validar. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del nombre del elemento. Este parámetro puede ser **nullptr**. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method


Valida el elemento en el contexto actual con los valores de los atributos **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** y **xsi:NoNamespaceSchemaLocation** especificados.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | const String\& | El nombre local del elemento a validar. |
| namespaceUri | const String\& | El URI del espacio de nombres del elemento a validar. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del nombre del elemento. Este parámetro puede ser **nullptr**. |
| xsiType | const String\& | El valor del atributo **xsi:Type** del elemento. Este parámetro puede ser **nullptr**. |
| xsiNil | const String\& | El valor del atributo **xsi:Nil** del elemento. Este parámetro puede ser **nullptr**. |
| xsiSchemaLocation | const String\& | El valor del atributo **xsi:SchemaLocation** del elemento. Este parámetro puede ser **nullptr**. |
| xsiNoNamespaceSchemaLocation | const String\& | El valor del atributo **xsi:NoNamespaceSchemaLocation** del elemento. Este parámetro puede ser **nullptr**. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
