---
title: System::Xml::ConformanceLevel enum
linktitle: ConformanceLevel
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::ConformanceLevel enum. Specifies the amount of input or output checking that XmlReader and XmlWriter objects perform in C++.'
type: docs
weight: 4600
url: /cpp/system.xml/conformancelevel/
---
## ConformanceLevel enum


Specifies the amount of input or output checking that [XmlReader](../xmlreader/) and [XmlWriter](../xmlwriter/) objects perform.

```cpp
enum class ConformanceLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | The [XmlReader](../xmlreader/) or [XmlWriter](../xmlwriter/) object automatically detects whether document-level or fragment-level checking should be performed, and does the appropriate checking. If you're wrapping another [XmlReader](../xmlreader/) or [XmlWriter](../xmlwriter/) object, the outer object doesn't do any additional conformance checking. Conformance checking is left up to the underlying object. |
| Fragment | 1 | The XML data is a [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), as defined by the W3C. This conformance level represents an XML document that might not have a root element but is otherwise well-formed. This level of checking ensures that the stream being read or written can be consumed by any processor as an [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | The XML data complies with the rules for a well-formed [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), as defined by the W3C. This level of checking ensures that the stream being read or written can be consumed by any processor as an [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
