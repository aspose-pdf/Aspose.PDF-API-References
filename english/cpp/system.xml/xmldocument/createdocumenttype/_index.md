---
title: System::Xml::XmlDocument::CreateDocumentType method
linktitle: CreateDocumentType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::CreateDocumentType method. Returns a new XmlDocumentType object in C++.'
type: docs
weight: 700
url: /cpp/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType method


Returns a new [XmlDocumentType](../../xmldocumenttype/) object.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | Name of the document type. |
| publicId | const String\& | The public identifier of the document type or **nullptr**. You can specify a public URI and also a system identifier to identify the location of the external DTD subset. |
| systemId | const String\& | The system identifier of the document type or **nullptr**. Specifies the URL of the file location for the external DTD subset. |
| internalSubset | const String\& | The DTD internal subset of the document type or **nullptr**. |

### ReturnValue

The new [XmlDocumentType](../../xmldocumenttype/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
