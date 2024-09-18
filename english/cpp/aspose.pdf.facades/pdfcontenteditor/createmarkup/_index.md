---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup method
linktitle: CreateMarkup
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup method. Creates markup annotation it PDF document in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor::CreateMarkup method


Creates markup annotation it PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup(System::Drawing::Rectangle rect, System::String contents, int32_t type, int32_t page, System::Drawing::Color clr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The rectangle defining the location of the annotation on the page. |
| contents | System::String | The contents of the annotation. |
| type | int32_t | The type of markup annotation. Can be 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| page | int32_t | The number of original page where the annotation will be created. |
| clr | System::Drawing::Color | The color of markup. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The rectangle defining the location of the annotation on the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>contents</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The contents of the annotation.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>type</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The type of markup annotation. Can be 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of original page where the annotation will be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>clr</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The color of markup.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
