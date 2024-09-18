---
title: Aspose::Pdf::Facades::PdfContentEditor::DrawCurve method
linktitle: DrawCurve
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::DrawCurve method. Creates curve annotation in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor::DrawCurve method


Creates curve annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::DrawCurve(System::SharedPtr<LineInfo> lineInfo, int32_t page, System::Drawing::Rectangle annotRect, System::String annotContents)
```


| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | System::SharedPtr\<LineInfo\> | The instance of [LineInfo](../../lineinfo/) class. |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | System::String | The contents of the annotation. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>lineInfo</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The instance of <ref refid="class_aspose_1_1_pdf_1_1_facades_1_1_line_info" kindref="compound">LineInfo</ref> class.</para>
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
      <parametername>annotRect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation rectangle defining the location of the annotation on the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotContents</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The contents of the annotation.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LineInfo](../../lineinfo/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
