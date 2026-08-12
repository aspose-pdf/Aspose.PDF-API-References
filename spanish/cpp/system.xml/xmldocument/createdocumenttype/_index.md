---
title: "System::Xml::XmlDocument::CreateDocumentType método"
linktitle: "CreateDocumentType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDocument::CreateDocumentType método. Devuelve un nuevo objeto XmlDocumentType en C++."
type: docs
weight: 700
url: /es/cpp/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType method


Devuelve un nuevo objeto [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | const String\& | Nombre del tipo de documento. |
| publicId | const String\& | El identificador público del tipo de documento o **nullptr**. Puede especificar un URI público y también un identificador de sistema para identificar la ubicación del subconjunto DTD externo. |
| systemId | const String\& | El identificador de sistema del tipo de documento o **nullptr**. Especifica la URL de la ubicación del archivo para el subconjunto DTD externo. |
| internalSubset | const String\& | El subconjunto interno DTD del tipo de documento o **nullptr**. |

### ReturnValue

El nuevo [XmlDocumentType](../../xmldocumenttype/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
