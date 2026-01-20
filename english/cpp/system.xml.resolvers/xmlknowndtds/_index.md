---
title: System::Xml::Resolvers::XmlKnownDtds enum
linktitle: XmlKnownDtds
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlKnownDtds enum. The Resolvers::XmlKnownDtds enumeration is used by the Resolvers::XmlPreloadedResolver and defines which well-known DTDs that the Resolvers::XmlPreloadedResolver recognizes in C++.'
type: docs
weight: 200
url: /cpp/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enum


The [Resolvers::XmlKnownDtds](./) enumeration is used by the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) and defines which well-known DTDs that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) recognizes.

```cpp
enum class XmlKnownDtds
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Specifies that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) will not recognize any of the predefined DTDs. |
| Xhtml10 | 1 | Specifies that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) will recognize DTDs and entities that are defined in XHTML 1.0. |
| Rss091 | 2 | Specifies that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) will recognize DTDs and entities that are defined in RSS 0.91. |
| All | 65535 | Specifies that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) will recognize all currently supported DTDs. This is the default behavior. |

## See Also

* Namespace [System::Xml::Resolvers](../)
* Library [Aspose.PDF for C++](../../)
