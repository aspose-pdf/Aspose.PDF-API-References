---
title: Aspose::Pdf::Facades::PdfFileStamp::AddHeader method
linktitle: AddHeader
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileStamp::AddHeader method. Adds header to the page in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf.facades/pdffilestamp/addheader/
---
## PdfFileStamp::AddHeader(System::SharedPtr\<FormattedText\>, float) method


Adds header to the page.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::SharedPtr<FormattedText> formattedText, float topMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | [Text](../../../aspose.pdf.text/) for header and properties of the text. |
| topMargin | float | Margin on the top of page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>formattedText</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> for header and properties of the text.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin on the top of page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddHeader(System::SharedPtr\<FormattedText\>, float, float, float) method


Adds header to the pages of file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::SharedPtr<FormattedText> formattedText, float topMargin, float leftMargin, float rightMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | System::SharedPtr\<FormattedText\> | Formatted text object which contains page text and its properties. |
| topMargin | float | Margin on the top of the page. |
| leftMargin | float | Margin on the left of the page. |
| rightMargin | float | Margin on the right of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>formattedText</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Formatted text object which contains page text and its properties.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin on the top of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin on the left of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin on the right of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddHeader(System::String, float) method


Adds image as header to the pages of the file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::String imageFile, float topMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | System::String | Path to the image file. |
| topMargin | float | Margin at top of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>imageFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to the image file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at top of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddHeader(System::String, float, float, float) method


Adds image as header on the pages.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::String imageFile, float topMargin, float leftMargin, float rightMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | System::String | Path to the image file. |
| topMargin | float | Margin at top of the page. |
| leftMargin | float | Margin at left side of the page. |
| rightMargin | float | Margin at right side of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>imageFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to the image file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at top of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at left side of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at right side of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddHeader(System::SharedPtr\<System::IO::Stream\>, float) method


Adds image as header on the pages.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::SharedPtr<System::IO::Stream> imageStream, float topMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | System::SharedPtr\<System::IO::Stream\> | Stream of the image. |
| topMargin | float | Margin at top of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>imageStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of the image.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at top of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddHeader(System::SharedPtr\<System::IO::Stream\>, float, float, float) method


Adds image at the top of the page.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfFileStamp::AddHeader(System::SharedPtr<System::IO::Stream> inputStream, float topMargin, float leftMargin, float rightMargin)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream which contains image data. |
| topMargin | float | Margin at top of the page. |
| leftMargin | float | Margin at left side of the page. |
| rightMargin | float | Margin at right side of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream which contains image data.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>topMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at top of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at left side of the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightMargin</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Margin at right side of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
