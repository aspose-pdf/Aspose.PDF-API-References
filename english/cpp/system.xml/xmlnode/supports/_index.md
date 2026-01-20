---
title: System::Xml::XmlNode::Supports method
linktitle: Supports
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode::Supports method. Tests if the DOM implementation implements a specific feature in C++.'
type: docs
weight: 4400
url: /cpp/system.xml/xmlnode/supports/
---
## XmlNode::Supports method


Tests if the DOM implementation implements a specific feature.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


| Parameter | Type | Description |
| --- | --- | --- |
| feature | String | The package name of the feature to test. This name is not case-sensitive. |
| version | String | The version number of the package name to test. If the version is not specified (null), supporting any version of the feature causes the method to return true. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Remarks



The following table describes the combinations that return **true**. |||
|-|-|
|Feature |Version|
|XML |1.0 |
|XML |2.0 |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
