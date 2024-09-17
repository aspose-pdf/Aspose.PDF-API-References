---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateLine method
linktitle: CreateLine
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateLine method. Creates line annotation in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor::CreateLine method


Creates line annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateLine(System::Drawing::Rectangle rect, System::String contents, float x1, float y1, float x2, float y2, int32_t page, int32_t border, System::Drawing::Color clr, System::String borderStyle, System::ArrayPtr<int32_t> dashArray, System::ArrayPtr<System::String> LEArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | System::String | The contents of the annotation. |
| x1 | float | The starting horizontal coordinate of the line. |
| y1 | float | The starting vertical coordinate of the line. |
| x2 | float | The ending horizontal coordinate of the line. |
| y2 | float | The ending vertical coordinate of the line. |
| page | int32_t | The number of original page where the annotation will be created. |
| border | int32_t | The border width in points. If this value is 0 no border is drawn. Default value is 1. |
| clr | System::Drawing::Color | The color of line. |
| borderStyle | System::String | The border style specifying the width and dash pattern to be used in drawing the line. This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | System::ArrayPtr\<int32_t\> | A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border. If it is used, borderSyle must be accordingly set to "D". |
| LEArray | System::ArrayPtr\<System::String\> | An array of two values respectively specifying the beginning and ending style of the drawing line. The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation rectangle defining the location of the annotation on the page.</para>
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
      <parametername>x1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The starting horizontal coordinate of the line.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The starting vertical coordinate of the line.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The ending horizontal coordinate of the line.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The ending vertical coordinate of the line.</para>
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
      <parametername>border</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The border width in points. If this value is 0 no border is drawn. Default value is 1.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>clr</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The color of line.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>borderStyle</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The border style specifying the width and dash pattern to be used in drawing the line. This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dashArray</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border. If it is used, borderSyle must be accordingly set to "D".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>LEArray</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>An array of two values respectively specifying the beginning and ending style of the drawing line. The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash".</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
