---
title: System::Xml::Schema::XmlSchemaSet::Schemas method
linktitle: Schemas
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSet::Schemas method. Returns a collection of all the XML Schema definition language (XSD) schemas in the XmlSchemaSet in C++.'
type: docs
weight: 1600
url: /cpp/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


Returns a collection of all the XML [Schema](../../) definition language (XSD) schemas in the [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### ReturnValue

An IList object containing all the schemas that have been added to the [XmlSchemaSet](../). If no schemas have been added to the [XmlSchemaSet](../), an empty collection is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaSet::Schemas(String) method


Returns a collection of all the XML [Schema](../../) definition language (XSD) schemas in the [XmlSchemaSet](../) that belong to the given namespace.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | String | The schema **targetNamespace** property. |

### ReturnValue

An IList object containing all the schemas that have been added to the [XmlSchemaSet](../) that belong to the given namespace. If no schemas have been added to the [XmlSchemaSet](../), an empty collection is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
