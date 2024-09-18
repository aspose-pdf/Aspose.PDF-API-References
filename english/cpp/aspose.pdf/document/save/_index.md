---
title: Aspose::Pdf::Document::Save method
linktitle: Save
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Save method. Stores document into stream in C++.'
type: docs
weight: 8400
url: /cpp/aspose.pdf/document/save/
---
## Document::Save(System::SharedPtr\<System::IO::Stream\>) method


Stores document into stream.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::SharedPtr<System::IO::Stream> output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| output | System::SharedPtr\<System::IO::Stream\> | Stream where document shell be stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where document shell be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::String) method


Saves document into the specified file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | System::String | Path to file where the document will be stored. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save() method


Save document incrementally (i.e. using incremental update technique).

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save()
```

## Remarks


In order to save document incrementally we should open the document file for writing. Therefore [Document](../) must be initialized with writable stream like in the next code snippet: [Document](../) doc = new [Document](../)(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // make some changes and save the document incrementally doc.Save(); 
## See Also

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::SharedPtr\<SaveOptions\>) method


Saves the document with save options.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::SharedPtr<SaveOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | System::SharedPtr\<SaveOptions\> | Save options. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Save options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::String, SaveFormat) method


Saves the document with a new name along with a file format.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::String outputFileName, SaveFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | System::String | Path to file where the document will be stored. |
| format | SaveFormat | Format options. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Format options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::SharedPtr\<System::IO::Stream\>, SaveFormat) method


Saves the document with a new name along with a file format.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::SharedPtr<System::IO::Stream> outputStream, SaveFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where the document will be stored. |
| format | SaveFormat | Format options. |
## Remarks


<parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="" kindref="compound">ArgumentException</ref> when <ref refid="class_aspose_1_1_pdf_1_1_html_save_options" kindref="compound">HtmlSaveOptions</ref> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Format options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [SaveFormat](../../saveformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::String, System::SharedPtr\<SaveOptions\>) method


Saves the document with a new name setting its save options.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::String outputFileName, System::SharedPtr<SaveOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | System::String | Path to file where the document will be stored. |
| options | System::SharedPtr\<SaveOptions\> | Save options. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Save options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) method


Saves the document to a stream with a save options.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<SaveOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where the document will be stored. |
| options | System::SharedPtr\<SaveOptions\> | Save options. |
## Remarks


<parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="" kindref="compound">ArgumentException</ref> when <ref refid="class_aspose_1_1_pdf_1_1_html_save_options" kindref="compound">HtmlSaveOptions</ref> is passed to a method. Save a document to the html stream is not supported. Please use method save to the file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Save options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Save(System::SharedPtr\<System::Web::HttpResponse\>, System::String, ContentDisposition, System::SharedPtr\<SaveOptions\>) method


Saves the document to a response stream with a save options.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Save(System::SharedPtr<System::Web::HttpResponse> response, System::String outputFileName, ContentDisposition disposition, System::SharedPtr<SaveOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Encapsulates HTTP-response information. |
| outputFileName | System::String | Simple file name, i.e. without path. |
| disposition | ContentDisposition | Represents a MIME protocol Content-Disposition header. |
| options | System::SharedPtr\<SaveOptions\> | Save options. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Encapsulates HTTP-response information.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Simple file name, i.e. without path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>disposition</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Represents a MIME protocol Content-Disposition header.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Save options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ContentDisposition](../../contentdisposition/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
