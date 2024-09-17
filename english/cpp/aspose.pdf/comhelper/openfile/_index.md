---
title: Aspose::Pdf::ComHelper::OpenFile method
linktitle: OpenFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ComHelper::OpenFile method. Just create and return Document using filename . The same as Document(Stream) in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/comhelper/openfile/
---
## ComHelper::OpenFile(System::String) method


Just create and return [Document](../../document/) using *filename* . The same as [Document(Stream)](../).

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(System::String filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The name of the pdf document file. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>filename</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of the pdf document file. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(System::String, System::String) method


Initialize and return new instance of the [Document](../../document/) class for working with encrypted document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(System::String filename, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../../document/) file name. |
| password | System::String | User or owner password. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>filename</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>password</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>User or owner password.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(System::String, System::String, bool) method


Initialize new instance of the [Document](../../document/) class for working with encrypted document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(System::String filename, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../../document/) file name. |
| password | System::String | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>filename</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>password</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>User or owner password.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>isManagedStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>if set to <computeroutput>true</computeroutput> inner stream is closed before exit; otherwise, is not.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(System::String, System::SharedPtr\<LoadOptions\>) method


Open an existing document from a file providing necessary converting oprions to get pdf document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(System::String filename, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | Input file to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *filename*  into pdf document. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>filename</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file to convert into pdf document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Represents properties for converting <emphasis>filename</emphasis>  into pdf document. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
