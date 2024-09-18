---
title: Aspose::Pdf::TeXFileSystemInputDirectory::GetFile method
linktitle: GetFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXFileSystemInputDirectory::GetFile method. Returns the stream to read from in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/texfilesysteminputdirectory/getfile/
---
## TeXFileSystemInputDirectory::GetFile method


Returns the stream to read from.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::IO::Stream> Aspose::Pdf::TeXFileSystemInputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false) override
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

* Class [TeXFileSystemInputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
