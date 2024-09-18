---
title: Aspose::Pdf::Document::Document constructor
linktitle: Document
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Document constructor. Initialize new Document instance from the input  stream in C++.'
type: docs
weight: 8200
url: /cpp/aspose.pdf/document/document/
---
## Document::Document(System::SharedPtr\<System::IO::Stream\>) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream object, corresponding pdf is password protected. |
| password | System::String | User or owner password. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::String, bool) constructor


Initialize new [Document](../) instance from the *input*  stream.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Stream with pdf document. |
| password | System::String | User or owner password. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |
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
      <para>If set to <computeroutput>true</computeroutput> inner stream is closed before exit; otherwise, is not.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::String filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The name of the pdf document file. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, bool) constructor


Just init [Document](../) using *filename* . The same as [Document(Stream)](../).

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::String filename, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The name of the pdf document file. |
| isManagedStream | bool | If set to **true** inner stream is closed before exit; otherwise, is not. |
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
  <parameteritem>
    <parameternamelist>
      <parametername>isManagedStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If set to <computeroutput>true</computeroutput> inner stream is closed before exit; otherwise, is not.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::String filename, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::String, bool) constructor


Initializes new instance of the [Document](../) class for working with encrypted document.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::String filename, System::String password, bool isManagedStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | [Document](../) file name. |
| password | System::String | User or owner password. |
| isManagedStream | bool | if set to **true** inner stream is closed before exit; otherwise, is not. |
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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document() constructor


Initializes empty document.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document()
```

## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(PdfVersion) constructor


Initializes empty document by version.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(PdfVersion version)
```


| Parameter | Type | Description |
| --- | --- | --- |
| version | PdfVersion | The PDF version. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>version</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The PDF version.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfVersion](../../pdfversion/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::String, System::SharedPtr\<LoadOptions\>) constructor


Opens an existing document from a file providing necessary converting options to get pdf document.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::String filename, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | Input file to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *filename*  into pdf document. |
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

* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) constructor


Opens an existing document from a stream providing necessary converting to get pdf document.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Document::Document(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream to convert into pdf document. |
| options | System::SharedPtr\<LoadOptions\> | Represents properties for converting *input*  into pdf document. |
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

* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
