---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateText method
linktitle: CreateText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateText method. Creates text annotation in PDF document in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor::CreateText method


Creates text annotation in PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateText(System::Drawing::Rectangle rect, System::String title, System::String contents, bool open, System::String icon, int32_t page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| title | System::String | The title of the annotation. |
| contents | System::String | The contents of the annotation. |
| open | bool | A flag specifying whether the annotation should initially be displayed open. |
| icon | System::String | The name of an icon will be used in displaying the annotation. This value can be: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | int32_t | The number of original page where the text annotation will be created. |
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
      <parametername>title</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The title of the annotation.</para>
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
      <parametername>open</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A flag specifying whether the annotation should initially be displayed open.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>icon</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of an icon will be used in displaying the annotation. This value can be: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert"</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of original page where the text annotation will be created.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
