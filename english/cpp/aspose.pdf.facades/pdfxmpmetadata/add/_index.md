---
title: Aspose::Pdf::Facades::PdfXmpMetadata::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata::Add method. Adds value to XMP metadata in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/add/
---
## PdfXmpMetadata::Add(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) method


Adds value to XMP metadata.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const DefaultMetadataProperties &key, const System::SharedPtr<XmpValue> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const DefaultMetadataProperties\& | The key name. |
| value | const System::SharedPtr\<XmpValue\>\& | Value which will be added. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The key name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Value which will be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(System::SharedPtr\<XmpPdfAExtensionObject\>, System::String, System::String, System::String) method


Adds extension field into metadata.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Add(System::SharedPtr<XmpPdfAExtensionObject> xmpPdfAExtensionObject, System::String namespacePrefix, System::String namespaceUri, System::String schemaDescription)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | System::SharedPtr\<XmpPdfAExtensionObject\> | The pdf extension object to add. |
| namespacePrefix | System::String | The prefix of schema. |
| namespaceUri | System::String | The namespace uri of schema. |
| schemaDescription | System::String | The optional description of schema. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>xmpPdfAExtensionObject</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf extension object to add.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>namespacePrefix</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The prefix of schema.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>namespaceUri</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The namespace uri of schema.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>schemaDescription</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The optional description of schema.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::String\&, const System::SharedPtr\<XmpValue\>\&) method


Adds new element to the dictionary object.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::String &key, const System::SharedPtr<XmpValue> &value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key of new element. |
| value | const System::SharedPtr\<XmpValue\>\& | Value of the element. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key of new element.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Value of the element.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::String\&, const System::SharedPtr\<System::Object\>\&) method


Adds new element to the dictionary object.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::String &key, const System::SharedPtr<System::Object> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key of new element. |
| value | const System::SharedPtr\<System::Object\>\& | Value of the element. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key of new element.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Value of the element.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Add(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Adds pair with key and value into the dictionary.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfXmpMetadata::Add(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Item to be added. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Item to be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
