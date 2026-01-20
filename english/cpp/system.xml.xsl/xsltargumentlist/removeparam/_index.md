---
title: System::Xml::Xsl::XsltArgumentList::RemoveParam method
linktitle: RemoveParam
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltArgumentList::RemoveParam method. Removes the parameter from the XsltArgumentList in C++.'
type: docs
weight: 800
url: /cpp/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam method


Removes the parameter from the [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the parameter to remove. [XsltArgumentList](../) does not check to ensure the name passed is a valid local name; however, the name cannot be **nullptr**. |
| namespaceUri | const String\& | The namespace URI of the parameter to remove. |

### ReturnValue

The parameter object or **nullptr** if one was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
