---
title: Aspose::Pdf::Devices::DocumentDevice::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::DocumentDevice::Process method. Each device represents some operation on the document, e.g. we can convert pdf document into another format in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.devices/documentdevice/process/
---
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Each device represents some operation on the document, e.g. we can convert pdf document into another format.

```cpp
virtual ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | The document to process. |
| fromPage | int32_t | Defines the page from which to start processing. |
| toPage | int32_t | Defines the last page to process. |
| output | System::SharedPtr\<System::IO::Stream\> | Defines stream where the results of processing are stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fromPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines the page from which to start processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>toPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines the last page to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines stream where the results of processing are stored. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) method


Processes the whole document and saves results into stream.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, System::SharedPtr<System::IO::Stream> output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | The document to process. |
| output | System::SharedPtr\<System::IO::Stream\> | Defines stream where the results of processing are stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines stream where the results of processing are stored. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) method


Processes the whole document and saves results into file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | The document to process. |
| outputFileName | System::String | Defines file where the results of processing are stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines file where the results of processing are stored. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::String) method


Processes certain pages of the document and saves results into file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Aspose::Pdf::Document\> | The document to process. |
| fromPage | int32_t | The first page to start processing. |
| toPage | int32_t | The last page of processing. |
| outputFileName | System::String | Defines file where the results of processing are stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fromPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page to start processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>toPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The last page of processing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Defines file where the results of processing are stored. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
