---
title: Aspose::Pdf::Page::SendTo method
linktitle: SendTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page::SendTo method. Sends page to process with given page device in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf/page/sendto/
---
## Page::SendTo(System::SharedPtr\<Devices::PageDevice\>, System::SharedPtr\<System::IO::Stream\>) method


Sends page to process with given page device.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Page::SendTo(System::SharedPtr<Devices::PageDevice> device, System::SharedPtr<System::IO::Stream> output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::PageDevice\> | The device to process page. |
| output | System::SharedPtr\<System::IO::Stream\> | Result stream which is used with device to save its output. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The device to process page. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Result stream which is used with device to save its output. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageDevice](../../../aspose.pdf.devices/pagedevice/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::SendTo(System::SharedPtr\<Devices::PageDevice\>, System::String) method


Sends page to process with given page device.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Page::SendTo(System::SharedPtr<Devices::PageDevice> device, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| device | System::SharedPtr\<Devices::PageDevice\> | The device to process page. |
| outputFileName | System::String | File which is used with device to save its output. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>device</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The device to process page. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File which is used with device to save its output. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageDevice](../../../aspose.pdf.devices/pagedevice/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
