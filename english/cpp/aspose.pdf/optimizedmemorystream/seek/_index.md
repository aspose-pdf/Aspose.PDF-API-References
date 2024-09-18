---
title: Aspose::Pdf::OptimizedMemoryStream::Seek method
linktitle: Seek
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OptimizedMemoryStream::Seek method. When overridden in a derived class, sets the position within the current stream in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf/optimizedmemorystream/seek/
---
## OptimizedMemoryStream::Seek method


When overridden in a derived class, sets the position within the current stream.

```cpp
ASPOSE_PDF_SHARED_API int64_t Aspose::Pdf::OptimizedMemoryStream::Seek(int64_t offset, System::IO::SeekOrigin origin) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| offset | int64_t | A byte offset relative to the *origin*  parameter. |
| origin | System::IO::SeekOrigin | A value of type [T:System::IO::SeekOrigin](../) indicating the reference point used to obtain the new position. |

### ReturnValue

The new position within the current stream.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>offset</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A byte offset relative to the <emphasis>origin</emphasis>  parameter.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>origin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A value of type <ref refid="" kindref="compound">T:System::IO::SeekOrigin</ref> indicating the reference point used to obtain the new position.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
