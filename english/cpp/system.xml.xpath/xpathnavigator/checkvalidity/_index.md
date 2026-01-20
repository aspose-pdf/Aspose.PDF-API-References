---
title: System::Xml::XPath::XPathNavigator::CheckValidity method
linktitle: CheckValidity
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::CheckValidity method. Verifies that the XML data in the XPathNavigator conforms to the XML Schema definition language (XSD) schema provided in C++.'
type: docs
weight: 300
url: /cpp/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity method


Verifies that the XML data in the [XPathNavigator](../) conforms to the XML [Schema](../../../system.xml.schema/) definition language (XSD) schema provided.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| schemas | SharedPtr\<System::Xml::Schema::XmlSchemaSet\> | The XmlSchemaSet containing the schemas used to validate the XML data contained in the [XPathNavigator](../). |
| validationEventHandler | System::Xml::Schema::ValidationEventHandler | The ValidationEventHandler that receives information about schema validation warnings and errors. |

### ReturnValue

**true** if no schema validation errors occurred; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
