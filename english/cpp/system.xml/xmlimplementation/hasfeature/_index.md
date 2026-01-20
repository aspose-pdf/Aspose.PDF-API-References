---
title: System::Xml::XmlImplementation::HasFeature method
linktitle: HasFeature
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlImplementation::HasFeature method. Tests if the Document Object Model (DOM) implementation implements a specific feature in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature method


Tests if the Document [Object](../../../system/object/) Model (DOM) implementation implements a specific feature.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


| Parameter | Type | Description |
| --- | --- | --- |
| strFeature | const String\& | The package name of the feature to test. This name is not case-sensitive. |
| strVersion | const String\& | This is the version number of the package name to test. If the version is not specified (**nullptr**), supporting any version of the feature causes the method to return **true**. |

### ReturnValue

**true** if the feature is implemented in the specified version; otherwise, **false**.
## Remarks



The following table shows the combinations that cause **HasFeature** to return **true**. |||
|-|-|
|strFeature |strVersion |
|XML |1.0 |
|XML |2.0 |

## See Also

* Class [String](../../../system/string/)
* Class [XmlImplementation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
