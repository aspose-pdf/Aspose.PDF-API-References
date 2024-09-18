---
title: Aspose::Pdf::Facades::PdfContentEditor::ReplaceText method
linktitle: ReplaceText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::ReplaceText method. Replaces text in the PDF file on the specified page. TextState object (font family, color) can be specified to replaced text in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## PdfContentEditor::ReplaceText(System::String, int32_t, System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) method


Replaces text in the PDF file on the specified page. [TextState](../) object (font family, color) can be specified to replaced text.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, int32_t thePage, System::String destString, System::SharedPtr<Aspose::Pdf::Text::TextState> textState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The string to be replaced. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) number (0 means "all pages"). |
| destString | System::String | The replaced string. |
| textState | System::SharedPtr\<Aspose::Pdf::Text::TextState\> | [Text](../../../aspose.pdf.text/) state ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc). |

### ReturnValue

Returns true if replacement was made.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The string to be replaced.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>thePage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> number (0 means "all pages").</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The replaced string.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textState</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> state (<ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref><ref refid="class_aspose_1_1_pdf_1_1_color" kindref="compound">Color</ref>, Font etc).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String) method


Replaces text in the PDF file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The string to be replaced. |
| destString | System::String | Replacing string. |

### ReturnValue

Returns true if replacement was made.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The string to be replaced.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Replacing string.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, int32_t, System::String) method


Replaces text in the PDF file on the specified page.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, int32_t thePage, System::String destString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | The sting to be replaced. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) number (0 for all pages) |
| destString | System::String | Replacing string. |

### ReturnValue

Returns true if replacement was made.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The sting to be replaced.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>thePage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> number (0 for all pages)</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Replacing string.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String, System::SharedPtr\<Aspose::Pdf::Text::TextState\>) method


Replaces text in the PDF file using specified [TextState](../) object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString, System::SharedPtr<Aspose::Pdf::Text::TextState> textState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | String to be replaced |
| destString | System::String | Replacing string |
| textState | System::SharedPtr\<Aspose::Pdf::Text::TextState\> | [Text](../../../aspose.pdf.text/) state ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc) |

### ReturnValue

Returns true if replacement was made.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>String to be replaced</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Replacing string</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>textState</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> state (<ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref><ref refid="class_aspose_1_1_pdf_1_1_color" kindref="compound">Color</ref>, Font etc)</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(System::String, System::String, int32_t) method


Replaces text in the PDF file and sets font size.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(System::String srcString, System::String destString, int32_t fontSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcString | System::String | String to be replaced. |
| destString | System::String | Replacing string. |
| fontSize | int32_t | Font size. |

### ReturnValue

Returns true if replacement was made.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>srcString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>String to be replaced.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destString</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Replacing string.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fontSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Font size.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
