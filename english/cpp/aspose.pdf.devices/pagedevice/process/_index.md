---
title: Aspose::Pdf::Devices::PageDevice::Process method
linktitle: Process
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Devices::PageDevice::Process method. Perfoms some operation on the given page, e.g. converts page into graphic image in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.devices/pagedevice/process/
---
## PageDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Perfoms some operation on the given page, e.g. converts page into graphic image.

```cpp
virtual ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to process. |
| output | System::SharedPtr\<System::IO::Stream\> | This stream contains the results of processing. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>This stream contains the results of processing. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## PageDevice::Process(System::SharedPtr\<Page\>, System::String) method


Perfoms some operation on the given page and saves results into the file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to process. |
| outputFileName | System::String | This file contains the results of processing. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page to process. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>This file contains the results of processing. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
