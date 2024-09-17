---
title: Aspose::Pdf::Devices::JpegDevice::JpegDevice constructor
linktitle: JpegDevice
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::JpegDevice::JpegDevice constructor. Initializes a new instance of the JpegDevice class with default resolution and maximum quality in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.devices/jpegdevice/jpegdevice/
---
## JpegDevice::JpegDevice() constructor


Initializes a new instance of the [JpegDevice](../) class with default resolution and maximum quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice()
```

## See Also

* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) constructor


Initializes a new instance of the [JpegDevice](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution)
```

## See Also

* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(int32_t) constructor


Initializes a new instance of the [JpegDevice](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| quality | int32_t | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) constructor


Initializes a new instance of the [JpegDevice](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution, int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| resolution | System::SharedPtr\<Aspose::Pdf::Devices::Resolution\> | [Resolution](../../resolution/) for the result image file, see [Resolution](../../resolution/) class. |
| quality | int32_t | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>resolution</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> for the result image file, see <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> class. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(int32_t, int32_t) constructor


Initializes a new instance of the [JpegDevice](../) class with provided image dimensions, default resolution (=150) and maximum quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(int32_t width, int32_t height)
```


| Parameter | Type | Description |
| --- | --- | --- |
| width | int32_t | [Image](../../../aspose.pdf/image/) output width. |
| height | int32_t | [Image](../../../aspose.pdf/image/) output height. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>width</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output width. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>height</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output height. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(System::SharedPtr\<PageSize\>) constructor


Initializes a new instance of the [JpegDevice](../) class with provided page size, default resolution (=150) and maximum quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size of the output image. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> size of the output image. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) constructor


Initializes a new instance of the [JpegDevice](../) class with provided image dimensions, resolution and maximum quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(int32_t width, int32_t height, System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution)
```


| Parameter | Type | Description |
| --- | --- | --- |
| width | int32_t | [Image](../../../aspose.pdf/image/) output width. |
| height | int32_t | [Image](../../../aspose.pdf/image/) output height. |
| resolution | System::SharedPtr\<Aspose::Pdf::Devices::Resolution\> | [Resolution](../../resolution/) for the result image file, see [Resolution](../../resolution/) class. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>width</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output width. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>height</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output height. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resolution</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> for the result image file, see <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> class. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) constructor


Initializes a new instance of the [JpegDevice](../) class with provided page size, resolution and maximum quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(System::SharedPtr<PageSize> pageSize, System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size of the output image. |
| resolution | System::SharedPtr\<Aspose::Pdf::Devices::Resolution\> | [Resolution](../../resolution/) for the result image file, see [Resolution](../../resolution/) class. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> size of the output image. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resolution</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> for the result image file, see <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> class. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(int32_t, int32_t, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) constructor


Initializes a new instance of the [JpegDevice](../) class with provided image dimensions, resolution and quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(int32_t width, int32_t height, System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution, int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| width | int32_t | [Image](../../../aspose.pdf/image/) output width. |
| height | int32_t | [Image](../../../aspose.pdf/image/) output height. |
| resolution | System::SharedPtr\<Aspose::Pdf::Devices::Resolution\> | [Resolution](../../resolution/) for the result image file, see [Resolution](../../resolution/) class. |
| quality | int32_t | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>width</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output width. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>height</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output height. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resolution</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> for the result image file, see <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> class. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## JpegDevice::JpegDevice(System::SharedPtr\<PageSize\>, System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>, int32_t) constructor


Initializes a new instance of the [JpegDevice](../) class with provided page size, resolution and quality.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Devices::JpegDevice::JpegDevice(System::SharedPtr<PageSize> pageSize, System::SharedPtr<Aspose::Pdf::Devices::Resolution> resolution, int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size of the output image. |
| resolution | System::SharedPtr\<Aspose::Pdf::Devices::Resolution\> | [Resolution](../../resolution/) for the result image file, see [Resolution](../../resolution/) class. |
| quality | int32_t | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> size of the output image. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resolution</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> for the result image file, see <ref refid="class_aspose_1_1_pdf_1_1_devices_1_1_resolution" kindref="compound">Resolution</ref> class. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>quality</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [Resolution](../../resolution/)
* Class [JpegDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
