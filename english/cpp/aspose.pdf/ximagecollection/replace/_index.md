---
title: Aspose::Pdf::XImageCollection::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XImageCollection::Replace method. Replace image in collection with another image in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf/ximagecollection/replace/
---
## XImageCollection::Replace(int32_t, System::SharedPtr\<System::IO::Stream\>) method


Replace image in collection with another image.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::XImageCollection::Replace(int32_t index, System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Index of collection item which will be replaced in [1..images count] range. |
| stream | System::SharedPtr\<System::IO::Stream\> | Stream containing image data (in JPEG format). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of collection item which will be replaced in [1..images count] range.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>stream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream containing image data (in JPEG format).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t, bool) method


Replace image in collection with another image.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::XImageCollection::Replace(int32_t index, System::SharedPtr<System::IO::Stream> stream, int32_t quality, bool isBlackAndWhite)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Index of collection item which will be replaced in [1..images count] range. |
| stream | System::SharedPtr\<System::IO::Stream\> | Stream containing image data (in JPEG format). |
| quality | int32_t | Quality of JPEG compression, in percent (valid vaues are 0..100). |
| isBlackAndWhite | bool | If true, image is compressed with CCITT compression method which provides better compression for black nad white image. May be used only for black and white images. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of collection item which will be replaced in [1..images count] range.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>stream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream containing image data (in JPEG format).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Quality of JPEG compression, in percent (valid vaues are 0..100).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>isBlackAndWhite</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If true, image is compressed with CCITT compression method which provides better compression for black nad white image. May be used only for black and white images.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t) method


Replace image in collection with another image.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::XImageCollection::Replace(int32_t index, System::SharedPtr<System::IO::Stream> stream, int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Index of collection item which will be replaced in [1..images count] range. |
| stream | System::SharedPtr\<System::IO::Stream\> | Stream containing image data (in JPEG format). |
| quality | int32_t | JPEG quality. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of collection item which will be replaced in [1..images count] range.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>stream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream containing image data (in JPEG format).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>JPEG quality.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
