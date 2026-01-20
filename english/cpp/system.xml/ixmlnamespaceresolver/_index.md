---
title: System::Xml::IXmlNamespaceResolver class
linktitle: IXmlNamespaceResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::IXmlNamespaceResolver class. Provides read-only access to a set of prefix and namespace mappings in C++.'
type: docs
weight: 400
url: /cpp/system.xml/ixmlnamespaceresolver/
---
## IXmlNamespaceResolver class


Provides read-only access to a set of prefix and namespace mappings.

```cpp
class IXmlNamespaceResolver : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) | Returns a collection of defined prefix-namespace mappings that are currently in scope. |
| virtual [LookupNamespace](./lookupnamespace/)(const String\&) | Returns the namespace URI mapped to the specified prefix. |
| virtual [LookupPrefix](./lookupprefix/)(const String\&) | Returns the prefix that is mapped to the specified namespace URI. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
