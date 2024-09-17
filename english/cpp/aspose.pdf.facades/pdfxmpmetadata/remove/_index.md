---
title: Aspose::Pdf::Facades::PdfXmpMetadata::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata::Remove method. Removes element with specified key in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## PdfXmpMetadata::Remove(DefaultMetadataProperties) method


Removes element with specified key.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Remove(DefaultMetadataProperties key)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Key of the element which will be deleted. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key of the element which will be deleted.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::String\&) method


Removes key from the dictionary.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key which will be removed. |

### ReturnValue

True - if key removed; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key which will be removed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

## See Also

* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Removes key/value pair from the collection.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Key/value pair to be removed. |

### ReturnValue

true if pair was found and removed.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key/value pair to be removed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
