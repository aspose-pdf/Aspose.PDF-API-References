---
title: System::Xml::Xsl::XsltContext::CompareDocument method
linktitle: CompareDocument
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltContext::CompareDocument method. When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the XslTransform class) in C++.'
type: docs
weight: 100
url: /cpp/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument method


When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../../xsltransform/) class).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | String | The base URI of the first document to compare. |
| nextbaseUri | String | The base URI of the second document to compare. |

### ReturnValue

An integer value describing the relative order of the two base URIs: -1 if **baseUri** occurs before **nextbaseUri**; 0 if the two base URIs are identical; and 1 if **baseUri** occurs after **nextbaseUri**.

## See Also

* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
