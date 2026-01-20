---
title: System::Xml::Schema::XmlSchemaValidator::ValidateElement method
linktitle: ValidateElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator::ValidateElement method. Validates the element in the current context in C++.'
type: docs
weight: 1700
url: /cpp/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Validates the element in the current context.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the element to validate. |
| namespaceUri | const String\& | The namespace URI of the element to validate. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the element's name. This parameter can be **nullptr**. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method


Validates the element in the current context with the **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, and **xsi:NoNamespaceSchemaLocation** attribute values specified.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the element to validate. |
| namespaceUri | const String\& | The namespace URI of the element to validate. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the element's name. This parameter can be **nullptr**. |
| xsiType | const String\& | The **xsi:Type** attribute value of the element. This parameter can be **nullptr**. |
| xsiNil | const String\& | The **xsi:Nil** attribute value of the element. This parameter can be **nullptr**. |
| xsiSchemaLocation | const String\& | The **xsi:SchemaLocation** attribute value of the element. This parameter can be **nullptr**. |
| xsiNoNamespaceSchemaLocation | const String\& | The **xsi:NoNamespaceSchemaLocation** attribute value of the element. This parameter can be **nullptr**. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
