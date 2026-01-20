---
title: System::Xml::XmlParserContext class
linktitle: XmlParserContext
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlParserContext class. Provides all the context information required by the XmlReader to parse an XML fragment in C++.'
type: docs
weight: 3000
url: /cpp/system.xml/xmlparsercontext/
---
## XmlParserContext class


Provides all the context information required by the [XmlReader](../xmlreader/) to parse an XML fragment.

```cpp
class XmlParserContext : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_BaseURI](./get_baseuri/)() | Returns the base URI. |
| [get_DocTypeName](./get_doctypename/)() | Returns the name of the document type declaration. |
| [get_Encoding](./get_encoding/)() | Returns the encoding type. |
| [get_InternalSubset](./get_internalsubset/)() | Returns the internal DTD subset. |
| [get_NamespaceManager](./get_namespacemanager/)() | Returns the [XmlNamespaceManager](../xmlnamespacemanager/). |
| [get_NameTable](./get_nametable/)() | Returns the [XmlNameTable](../xmlnametable/) used to atomize strings. For more information on atomized strings, see [XmlNameTable](../xmlnametable/). |
| [get_PublicId](./get_publicid/)() | Returns the public identifier. |
| [get_SystemId](./get_systemid/)() | Returns the system identifier. |
| [get_XmlLang](./get_xmllang/)() | Returns the current **xml:lang** scope. |
| [get_XmlSpace](./get_xmlspace/)() | Returns the current **xml:space** scope. |
| [set_BaseURI](./set_baseuri/)(const String\&) | Sets the base URI. |
| [set_DocTypeName](./set_doctypename/)(const String\&) | Sets the name of the document type declaration. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Sets the encoding type. |
| [set_InternalSubset](./set_internalsubset/)(const String\&) | Sets the internal DTD subset. |
| [set_NamespaceManager](./set_namespacemanager/)(const SharedPtr\<XmlNamespaceManager\>\&) | Sets the [XmlNamespaceManager](../xmlnamespacemanager/). |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Sets the [XmlNameTable](../xmlnametable/) used to atomize strings. For more information on atomized strings, see [XmlNameTable](../xmlnametable/). |
| [set_PublicId](./set_publicid/)(const String\&) | Sets the public identifier. |
| [set_SystemId](./set_systemid/)(const String\&) | Sets the system identifier. |
| [set_XmlLang](./set_xmllang/)(const String\&) | Sets the current **xml:lang** scope. |
| [set_XmlSpace](./set_xmlspace/)(System::Xml::XmlSpace) | Sets the current **xml:space** scope. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) | Initializes a new instance of the [XmlParserContext](./) class with the specified [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, and **xml:space** values. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Initializes a new instance of the [XmlParserContext](./) class with the specified [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space**, and encoding. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) | Initializes a new instance of the [XmlParserContext](./) class with the specified [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, and document type values. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Initializes a new instance of the [XmlParserContext](./) class with the specified [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, encoding, and document type values. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
