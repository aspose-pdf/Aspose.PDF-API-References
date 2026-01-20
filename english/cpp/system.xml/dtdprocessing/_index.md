---
title: System::Xml::DtdProcessing enum
linktitle: DtdProcessing
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::DtdProcessing enum. Specifies the options for processing DTDs. The DtdProcessing enumeration is used by the XmlReaderSettings class in C++.'
type: docs
weight: 4700
url: /cpp/system.xml/dtdprocessing/
---
## DtdProcessing enum


Specifies the options for processing DTDs. The [DtdProcessing](./) enumeration is used by the [XmlReaderSettings](../xmlreadersettings/) class.

```cpp
enum class DtdProcessing
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Prohibit | 0 | Specifies that when a DTD is encountered, an [XmlException](../xmlexception/) is thrown with a message that states that DTDs are prohibited. This is the default behavior. |
| Ignore | 1 | Causes the DOCTYPE element to be ignored. No DTD processing occurs, and the DTD/DOCTYPE is lost on output. |
| Parse | 2 | Used for parsing DTDs. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
