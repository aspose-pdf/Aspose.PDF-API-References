---
title: Aspose::Pdf::ComHelper::OpenStream method
linktitle: OpenStream
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ComHelper::OpenStream method. Initialize and return new Document instance from the input  stream in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/comhelper/openstream/
---
## ComHelper::OpenStream(System::SharedPtr\<System::IO::Stream\>) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(System::SharedPtr<System::IO::Stream> input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with pdf document. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(System::SharedPtr\<System::IO::Stream\>, System::String) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(System::SharedPtr<System::IO::Stream> input, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream object, corresponding pdf is password protected. |
| password | System::String | User or owner password. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream object, corresponding pdf is password protected.</para>
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
## ComHelper::OpenStream(System::SharedPtr\<System::IO::Stream\>, bool) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(System::SharedPtr<System::IO::Stream> input, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with pdf document. </para>
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
## ComHelper::OpenStream(System::SharedPtr\<System::IO::Stream\>, System::String, bool) method


Initialize and return new [Document](../../document/) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(System::SharedPtr<System::IO::Stream> input, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| password | System::String | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with pdf document. </para>
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
## ComHelper::OpenStream(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) method


Open and return an existing document from a stream providing necessary converting to get pdf document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *input*  into pdf document. |

### ReturnValue

[Document](../../document/) object
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream to convert into pdf document. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Represents properties for converting <emphasis>input</emphasis>  into pdf document. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
