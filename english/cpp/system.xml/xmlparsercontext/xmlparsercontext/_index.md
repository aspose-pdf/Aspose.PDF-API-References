---
title: System::Xml::XmlParserContext::XmlParserContext constructor
linktitle: XmlParserContext
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlParserContext::XmlParserContext constructor. Initializes a new instance of the XmlParserContext class with the specified XmlNameTable, XmlNamespaceManager, base URI, xml:lang, xml:space, and document type values in C++.'
type: docs
weight: 100
url: /cpp/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, and document type values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| docTypeName | const String\& | The name of the document type declaration. |
| pubId | const String\& | The public identifier. |
| sysId | const String\& | The system identifier. |
| internalSubset | const String\& | The internal DTD subset. The DTD subset is used for entity resolution, not for document validation. |
| baseURI | const String\& | The base URI for the XML fragment (the location from which the fragment was loaded). |
| xmlLang | const String\& | The **xml:lang** scope. |
| xmlSpace | System::Xml::XmlSpace | An [XmlSpace](../../xmlspace/) value indicating the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, encoding, and document type values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| docTypeName | const String\& | The name of the document type declaration. |
| pubId | const String\& | The public identifier. |
| sysId | const String\& | The system identifier. |
| internalSubset | const String\& | The internal DTD subset. The DTD is used for entity resolution, not for document validation. |
| baseURI | const String\& | The base URI for the XML fragment (the location from which the fragment was loaded). |
| xmlLang | const String\& | The **xml:lang** scope. |
| xmlSpace | System::Xml::XmlSpace | An [XmlSpace](../../xmlspace/) value indicating the **xml:space** scope. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | An Encoding object indicating the encoding setting. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, and **xml:space** values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| xmlLang | const String\& | The **xml:lang** scope. |
| xmlSpace | System::Xml::XmlSpace | An [XmlSpace](../../xmlspace/) value indicating the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, and encoding.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information on atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| xmlLang | const String\& | The **xml:lang** scope. |
| xmlSpace | System::Xml::XmlSpace | An [XmlSpace](../../xmlspace/) value indicating the **xml:space** scope. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | An Encoding object indicating the encoding setting. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
