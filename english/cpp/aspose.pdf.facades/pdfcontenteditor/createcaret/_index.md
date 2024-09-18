---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateCaret method
linktitle: CreateCaret
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateCaret method. Creates caret annotation in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor::CreateCaret method


Creates caret annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateCaret(int32_t page, System::Drawing::Rectangle annotRect, System::Drawing::Rectangle caretRect, System::String symbol, System::String annotContents, System::Drawing::Color color)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| caretRect | System::Drawing::Rectangle | The actual boundaries of the underlying caret. |
| symbol | System::String | A symbol will be associated with the caret. Value can be: "P" (Paragraph), "None". |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The color of the annotation. |
## Remarks


<parameterlist kind="param">
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
      <parametername>caretRect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The actual boundaries of the underlying caret.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>symbol</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A symbol will be associated with the caret. Value can be: "P" (Paragraph), "None".</para>
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
  <parameteritem>
    <parameternamelist>
      <parametername>color</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The color of the annotation.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>



## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
