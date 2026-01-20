---
title: System::Xml::XmlWriter::WriteDocType method
linktitle: WriteDocType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlWriter::WriteDocType method. When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes in C++.'
type: docs
weight: 1700
url: /cpp/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType method


When overridden in a derived class, writes the DOCTYPE declaration with the specified name and optional attributes.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the DOCTYPE. This must be non-empty. |
| pubid | const String\& | If non-null it also writes PUBLIC "pubid" "sysid" where **pubid** and **sysid** are replaced with the value of the given arguments. |
| sysid | const String\& | If **pubid** is **nullptr** and **sysid** is non-null it writes SYSTEM "sysid" where **sysid** is replaced with the value of this argument. |
| subset | const String\& | If non-null it writes [subset] where subset is replaced with the value of this argument. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
