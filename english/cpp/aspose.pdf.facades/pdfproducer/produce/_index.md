---
title: Aspose::Pdf::Facades::PdfProducer::Produce method
linktitle: Produce
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfProducer::Produce method. Produce the PDF stream using specified import format in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/pdfproducer/produce/
---
## PdfProducer::Produce(System::SharedPtr\<System::IO::Stream\>, ImportFormat, System::SharedPtr\<System::IO::Stream\>) method


Produce the PDF stream using specified import format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::SharedPtr<System::IO::Stream> inputStream, ImportFormat format, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| format | ImportFormat | Import format. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output PDF stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input or output stream is null</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ImportFormat](../../../aspose.pdf/importformat/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::String, ImportFormat, System::SharedPtr\<System::IO::Stream\>) method


Produce the PDF stream using specified import format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::String inputFileName, ImportFormat format, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | System::String | Input file name. |
| format | ImportFormat | Import format. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output PDF stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output stream is null</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ImportFormat](../../../aspose.pdf/importformat/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::SharedPtr\<System::IO::Stream\>, ImportFormat, System::String) method


Produce the PDF file using specified import format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::SharedPtr<System::IO::Stream> inputStream, ImportFormat format, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| format | ImportFormat | Import format. |
| outputFileName | System::String | Output PDF file |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF file</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream is null</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ImportFormat](../../../aspose.pdf/importformat/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::String, ImportFormat, System::String) method


Produce the PDF file using specified import format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::String inputFileName, ImportFormat format, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | System::String | Input file name. |
| format | ImportFormat | Import format. |
| outputFileName | System::String | Output PDF file |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF file</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input or output file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ImportFormat](../../../aspose.pdf/importformat/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::String, System::SharedPtr\<ImportOptions\>, System::SharedPtr\<System::IO::Stream\>) method


Produce the PDF stream using specified import option.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::String inputFileName, System::SharedPtr<ImportOptions> options, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | System::String | Input file name. |
| options | System::SharedPtr\<ImportOptions\> | Import option. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output PDF stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import option.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output stream is null</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ImportOptions](../../../aspose.pdf/importoptions/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ImportOptions\>, System::String) method


Produce the PDF file using specified import option.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<ImportOptions> options, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| options | System::SharedPtr\<ImportOptions\> | Import option. |
| outputFileName | System::String | Output PDF file. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import option.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream is null</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ImportOptions](../../../aspose.pdf/importoptions/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::String, System::SharedPtr\<ImportOptions\>, System::String) method


Produce the PDF file using specified import option.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::String inputFileName, System::SharedPtr<ImportOptions> options, System::String outputFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | System::String | Input file name. |
| options | System::SharedPtr\<ImportOptions\> | Import option. |
| outputFileName | System::String | Output PDF stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import option.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input or output file name is an empty string</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ImportOptions](../../../aspose.pdf/importoptions/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfProducer::Produce(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ImportOptions\>, System::SharedPtr\<System::IO::Stream\>) method


Produce the PDF file using specified import option.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfProducer::Produce(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<ImportOptions> options, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| options | System::SharedPtr\<ImportOptions\> | Import option. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output PDF stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Import option.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output PDF stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidFileFormatException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The exception is thrown when a file is invalid.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input or output stream is null.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ImportOptions](../../../aspose.pdf/importoptions/)
* Class [PdfProducer](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
