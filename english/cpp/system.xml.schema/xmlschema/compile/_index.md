---
title: System::Xml::Schema::XmlSchema::Compile method
linktitle: Compile
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchema::Compile method. Compiles the XML SchemaObject Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation in C++.'
type: docs
weight: 200
url: /cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Compiles the XML [Schema](../../)[Object](../../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | The validation event handler that receives information about XML [Schema](../../) validation errors. |

## See Also

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Compiles the XML [Schema](../../)[Object](../../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | The validation event handler that receives information about the XML [Schema](../../) validation errors. |
| resolver | const SharedPtr\<XmlResolver\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements. |

## See Also

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
