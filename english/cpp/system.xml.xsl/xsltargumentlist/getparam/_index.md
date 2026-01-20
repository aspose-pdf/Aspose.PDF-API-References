---
title: System::Xml::Xsl::XsltArgumentList::GetParam method
linktitle: GetParam
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltArgumentList::GetParam method. Returns the parameter associated with the namespace qualified name in C++.'
type: docs
weight: 600
url: /cpp/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam method


Returns the parameter associated with the namespace qualified name.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the parameter. [XsltArgumentList](../) does not check to ensure the name passed is a valid local name; however, the name cannot be **nullptr**. |
| namespaceUri | const String\& | The namespace URI associated with the parameter. |

### ReturnValue

The parameter object or **nullptr** if one was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
