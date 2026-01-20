---
title: System::Xml::XmlDocument::Validate method
linktitle: Validate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::Validate method. Validates the XmlDocument against the XML Schema Definition Language (XSD) schemas contained in the XmlDocument::get_Schemas list in C++.'
type: docs
weight: 4300
url: /cpp/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) method


Validates the [XmlDocument](../) against the XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schemas contained in the [XmlDocument::get_Schemas](../get_schemas/) list.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | The [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object that receives information about schema validation warnings and errors. |

## See Also

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) method


Validates the [XmlNode](../../xmlnode/) object specified against the XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schemas in the [XmlDocument::get_Schemas](../get_schemas/) list.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | Schema::ValidationEventHandler | The [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object that receives information about schema validation warnings and errors. |
| nodeToValidate | const SharedPtr\<XmlNode\>\& | The [XmlNode](../../xmlnode/) object created from an [XmlDocument](../) to validate. |

## See Also

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
