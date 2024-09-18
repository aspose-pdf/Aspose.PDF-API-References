---
title: Aspose::Pdf::OptimizedMemoryStream::Write method
linktitle: Write
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream::Write method. When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream::Write method


When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OptimizedMemoryStream::Write(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | An array of bytes. This method copies *count*  bytes from *buffer*  to the current stream. |
| offset | int32_t | The zero-based byte offset in *buffer*  at which to begin copying bytes to the current stream. |
| count | int32_t | The number of bytes to be written to the current stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>buffer</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>An array of bytes. This method copies <emphasis>count</emphasis>  bytes from <emphasis>buffer</emphasis>  to the current stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>offset</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The zero-based byte offset in <emphasis>buffer</emphasis>  at which to begin copying bytes to the current stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>count</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of bytes to be written to the current stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
The sum of *offset*  and *count*  is greater than the buffer length. 
## See Also

* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
