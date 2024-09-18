---
title: Aspose::Pdf::Document::Convert method
linktitle: Convert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Convert method. Convert document and save errors into the specified file in C++.'
type: docs
weight: 9000
url: /cpp/aspose.pdf/document/convert/
---
## Document::Convert(System::String, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Convert document and save errors into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(System::String outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | System::String | Path to file where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>action</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for objects that can not be converted</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>transparencyAction</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for image masked objects</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Convert document and save errors into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(System::SharedPtr<System::IO::Stream> outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | System::SharedPtr\<System::IO::Stream\> | Stream where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>action</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for objects that can not be converted</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>transparencyAction</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for image masked objects</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::String, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Convert document and save errors into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(System::String outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | System::String | Path to file where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>action</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for objects that can not be converted</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::SharedPtr\<PdfFormatConversionOptions\>) method


Convert document using specified conversion options.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(System::SharedPtr<PdfFormatConversionOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | System::SharedPtr\<PdfFormatConversionOptions\> | set of options for convert PDF document |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>set of options for convert PDF document</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocrWithPage, bool) method


Recognize images inside the document and add hocr strings over it.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocrWithPage callback, bool flattenImages=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | Document::CallBackGetHocrWithPage | Action for images that will be processed by hocr recognize. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### ReturnValue

The operation result. If there are no images in the document returns [false](../).
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>callback</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for images that will be processed by hocr recognize.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>flattenImages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> in pdf images can be painted using the mechanics of masks, in which case the images must be flattened.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Typedef [CallBackGetHocrWithPage](../callbackgethocrwithpage/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocr, bool) method


Recognize images inside the document and add hocr strings over it.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocr callback, bool flattenImages=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| callback | Document::CallBackGetHocr | Action for images that will be processed by hocr recognize. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### ReturnValue

The operation result. If there are no images in the document returns [false](../).
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>callback</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for images that will be processed by hocr recognize.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>flattenImages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> in pdf images can be painted using the mechanics of masks, in which case the images must be flattened.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Typedef [CallBackGetHocr](../callbackgethocr/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Convert document and save errors into the specified stream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(System::SharedPtr<System::IO::Stream> outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | System::SharedPtr\<System::IO::Stream\> | Stream where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | [Pdf](../../) format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>action</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action for objects that can not be converted</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, System::SharedPtr\<System::IO::Stream\>, bool, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Convert document by applying the Fixup.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(Fixup fixup, System::SharedPtr<System::IO::Stream> outputLog, bool onlyValidation=false, System::ArrayPtr<System::SharedPtr<System::Object>> parameters=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | System::SharedPtr\<System::IO::Stream\> | The log of process. |
| onlyValidation | bool | Only document validation. |
| parameters | System::ArrayPtr\<System::SharedPtr\<System::Object\>\> | Properties for Fixup that can not be set. |

### ReturnValue

The operation result.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fixup</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The Fixup type.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputLog</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The log of process.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>onlyValidation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Only document validation.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Properties for Fixup that can not be set.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [Fixup](../../fixup/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, System::String, bool, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Convert document by applying the Fixup.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Convert(Fixup fixup, System::String outputLog, bool onlyValidation=false, System::ArrayPtr<System::SharedPtr<System::Object>> parameters=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | System::String | The log of process. |
| onlyValidation | bool | Only document validation. |
| parameters | System::ArrayPtr\<System::SharedPtr\<System::Object\>\> | Properties for Fixup that can not be set. |

### ReturnValue

The operation result.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fixup</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The Fixup type.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputLog</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The log of process.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>onlyValidation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Only document validation.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Properties for Fixup that can not be set.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [Fixup](../../fixup/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::String, System::SharedPtr\<LoadOptions\>, System::String, System::SharedPtr\<SaveOptions\>) method


Converts source file in source format into destination file in destination format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Convert(System::String srcFileName, System::SharedPtr<LoadOptions> loadOptions, System::String dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | The source file name. |
| loadOptions | System::SharedPtr\<LoadOptions\> | The source file format. |
| dstFileName | System::String | The destination file name. |
| saveOptions | System::SharedPtr\<SaveOptions\> | The destination file format. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>loadOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source file format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dstFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>saveOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination file format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>, System::String, System::SharedPtr\<SaveOptions\>) method


Converts stream in source format into destination file in destination format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Convert(System::SharedPtr<System::IO::Stream> srcStream, System::SharedPtr<LoadOptions> loadOptions, System::String dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | System::SharedPtr\<System::IO::Stream\> | The source stream. |
| loadOptions | System::SharedPtr\<LoadOptions\> | The source stream format. |
| dstFileName | System::String | The destination file name. |
| saveOptions | System::SharedPtr\<SaveOptions\> | The destination file format. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>loadOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source stream format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dstFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>saveOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination file format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::String, System::SharedPtr\<LoadOptions\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) method


Converts source file in source format into stream in destination format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Convert(System::String srcFileName, System::SharedPtr<LoadOptions> loadOptions, System::SharedPtr<System::IO::Stream> dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | The source file name. |
| loadOptions | System::SharedPtr\<LoadOptions\> | The source file format. |
| dstStream | System::SharedPtr\<System::IO::Stream\> | The destination stream. |
| saveOptions | System::SharedPtr\<SaveOptions\> | The destination stream format. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>loadOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source file format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dstStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>saveOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination stream format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<SaveOptions\>) method


Converts stream in source format into stream in destination format.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::Convert(System::SharedPtr<System::IO::Stream> srcStream, System::SharedPtr<LoadOptions> loadOptions, System::SharedPtr<System::IO::Stream> dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | System::SharedPtr\<System::IO::Stream\> | The source stream. |
| loadOptions | System::SharedPtr\<LoadOptions\> | The source stream format. |
| dstStream | System::SharedPtr\<System::IO::Stream\> | The destination stream. |
| saveOptions | System::SharedPtr\<SaveOptions\> | The destination file format. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>loadOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The source stream format.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dstStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>saveOptions</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination file format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
