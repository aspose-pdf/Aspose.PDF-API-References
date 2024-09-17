---
title: Aspose::Pdf::ITeXInputDirectory::GetFile method
linktitle: GetFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ITeXInputDirectory::GetFile method. Returns the stream to read from or to write to in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/itexinputdirectory/getfile/
---
## ITeXInputDirectory::GetFile method


Returns the stream to read from or to write to.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Pdf::ITeXInputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | System::String | The file name. |
| fullName | System::String\& | The full file name. |
| searchSubdirectories | bool | Indicates whether to look for a file in subdirectories. |

### ReturnValue

The stream.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fullName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The full file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>searchSubdirectories</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Indicates whether to look for a file in subdirectories.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ITeXInputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
