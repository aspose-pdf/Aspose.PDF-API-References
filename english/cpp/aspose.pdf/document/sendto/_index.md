---
title: Aspose::Pdf::Document::SendTo method
linktitle: SendTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::SendTo method. Sends the whole document to the document device for processing in C++.'
type: docs
weight: 8600
url: /cpp/aspose.pdf/document/sendto/
---
## Document::SendTo(System::SharedPtr\<Devices::DocumentDevice\>, System::SharedPtr\<System::IO::Stream\>) method


Sends the whole document to the document device for processing.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::SendTo(System::SharedPtr<Devices::DocumentDevice> device, System::SharedPtr<System::IO::Stream> output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::DocumentDevice\> | [Document](../) device which is used to process the document. |
| output | System::SharedPtr\<System::IO::Stream\> | Output stream contains the results of the document processing with given device. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> device which is used to process the document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output stream contains the results of the document processing with given device. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(System::SharedPtr\<Devices::DocumentDevice\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Sends the certain pages of the document to the document device for processing.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::SendTo(System::SharedPtr<Devices::DocumentDevice> device, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::DocumentDevice\> | [Document](../) device which is used to process the document. |
| fromPage | int32_t | The first page for processing. |
| toPage | int32_t | The last page for processing. |
| output | System::SharedPtr\<System::IO::Stream\> | Output stream contains the results of the document pages processing with given device. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> device which is used to process the document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fromPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page for processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>toPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The last page for processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output stream contains the results of the document pages processing with given device. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(System::SharedPtr\<Devices::DocumentDevice\>, System::String) method


Sends the whole document to the document device for processing.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::SendTo(System::SharedPtr<Devices::DocumentDevice> device, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::DocumentDevice\> | [Document](../) device which is used to process the document. |
| outputFileName | System::String | Output file name with the results of processing. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> device which is used to process the document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file name with the results of processing. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(System::SharedPtr\<Devices::DocumentDevice\>, int32_t, int32_t, System::String) method


Sends the whole document to the document device for processing.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::SendTo(System::SharedPtr<Devices::DocumentDevice> device, int32_t fromPage, int32_t toPage, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::DocumentDevice\> | [Document](../) device which is used to process the document. |
| fromPage | int32_t | The first page for processing. |
| toPage | int32_t | The last page for processing. |
| outputFileName | System::String | Output file name with the results of processing. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> device which is used to process the document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fromPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page for processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>toPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The last page for processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file name with the results of processing. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
