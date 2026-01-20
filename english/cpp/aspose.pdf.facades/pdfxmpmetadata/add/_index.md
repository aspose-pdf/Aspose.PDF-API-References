---
title: Aspose::Pdf::Facades::PdfXmpMetadata::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata::Add method. Adds value to XMP metadata in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/add/
---
## PdfXmpMetadata::Add(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) method


Adds value to XMP metadata.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const DefaultMetadataProperties &key, const System::SharedPtr<XmpValue> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const DefaultMetadataProperties\& | The key name. |
| value | const System::SharedPtr\<XmpValue\>\& | Value which will be added. |

## See Also

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Adds pair with key and value into the dictionary.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Item to be added. |

## See Also

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::String\&, const System::SharedPtr\<System::Object\>\&) method


Adds new element to the dictionary object.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::String &key, const System::SharedPtr<System::Object> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key of new element. |
| value | const System::SharedPtr\<System::Object\>\& | Value of the element. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::String\&, const System::SharedPtr\<XmpValue\>\&) method


Adds new element to the dictionary object.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::String &key, const System::SharedPtr<XmpValue> &value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key of new element. |
| value | const System::SharedPtr\<XmpValue\>\& | Value of the element. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(System::SharedPtr\<XmpPdfAExtensionObject\>, System::String, System::String, System::String) method


Adds extension field into metadata.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Add(System::SharedPtr<XmpPdfAExtensionObject> xmpPdfAExtensionObject, System::String namespacePrefix, System::String namespaceUri, System::String schemaDescription)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | System::SharedPtr\<XmpPdfAExtensionObject\> | The pdf extension object to add. |
| namespacePrefix | System::String | The prefix of schema. |
| namespaceUri | System::String | The namespace uri of schema. |
| schemaDescription | System::String | The optional description of schema. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* Class [String](../../../system/string/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
