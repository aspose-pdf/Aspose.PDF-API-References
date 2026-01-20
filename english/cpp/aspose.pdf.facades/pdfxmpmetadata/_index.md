---
title: Aspose::Pdf::Facades::PdfXmpMetadata class
linktitle: PdfXmpMetadata
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata class. Class for manipulation with XMP metadata in C++.'
type: docs
weight: 3100
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class


Class for manipulation with XMP metadata.

```cpp
class PdfXmpMetadata : public Aspose::Pdf::Facades::SaveableFacade,
                       public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Adds value to XMP metadata. |
| [Add](./add/)(System::SharedPtr\<XmpPdfAExtensionObject\>, System::String, System::String, System::String) | Adds extension field into metadata. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Adds new element to the dictionary object. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Adds new element to the dictionary object. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Adds pair with key and value into the dictionary. |
| [Clear](./clear/)() override | Removes all elements from the object. |
| [Contains](./contains/)(const System::String\&) const | Checks if dictionary contains the specified key. |
| [Contains](./contains/)(const DefaultMetadataProperties\&) const | Checks if dictionary contains the specified property. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Checks does specified key-value pair is contained in the dictionary. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Copy metadata into array. |
| [get_Count](./get_count/)() const override | Gets count if items in the collection. |
| [get_ExtensionFields](./get_extensionfields/)() | Gets the dictionary of extension fields. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Returns true is collection has fixed size. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Returns true if collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if collection is synchronized. |
| [get_Keys](./get_keys/)() const override | Gets keys from the dictionary. |
| [get_Values](./get_values/)() const override | Gets the collection of values in dictionary. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator object of the dictionary. |
| [GetNamespaceURIByPrefix](./getnamespaceuribyprefix/)(System::String) | Gets namespace URI by prefix. |
| [GetPrefixByNamespaceURI](./getprefixbynamespaceuri/)(System::String) | Gets the prefix by namespace URI. |
| [GetXmpMetadata](./getxmpmetadata/)() | Get the XmpMetadata of the input pdf in a xml format. |
| [GetXmpMetadata](./getxmpmetadata/)(System::String) | Get a part of the XmpMetadata of the input pdf according to a meta name. |
| [idx_get](./idx_get/)(const System::String\&) const override | Gets value by key. |
| [idx_get](./idx_get/)(const DefaultMetadataProperties\&) const | Gets value of XMP metadata by key. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Sets value by key. |
| [idx_set](./idx_set/)(const DefaultMetadataProperties\&, System::SharedPtr\<XmpValue\>) | Gets value of XMP metadata by key. |
| [PdfXmpMetadata](./pdfxmpmetadata/)() | Constructor for [PdfXmpMetadata](./). |
| [PdfXmpMetadata](./pdfxmpmetadata/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfXmpMetadata](./) object on base of the *document* . |
| [RegisterNamespaceURI](./registernamespaceuri/)(System::String, System::String) | Registers the namespace URI. |
| [Remove](./remove/)(DefaultMetadataProperties) | Removes element with specified key. |
| [Remove](./remove/)(const System::String\&) override | Removes key from the dictionary. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Removes key/value pair from the collection. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Tries to find key in the dictionary and retreives value if found. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
