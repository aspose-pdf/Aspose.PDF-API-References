---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp method
linktitle: CreateRubberStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp method. Creates a rubber stamp annotation in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::String, System::Drawing::Color) method


Creates a rubber stamp annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String icon, System::String annotContents, System::Drawing::Color color)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| icon | System::String | An icon is to be used in displaying the annotation. Default value: 'Draft'. |
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
      <parametername>icon</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>An icon is to be used in displaying the annotation. Default value: 'Draft'.</para>
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
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::String) method


Creates a rubber stamp annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String annotContents, System::Drawing::Color color, System::String appearanceFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The colour of the annotation. |
| appearanceFile | System::String | The path of appearance file. |
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
      <para>The colour of the annotation.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>appearanceFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The path of appearance file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::SharedPtr\<System::IO::Stream\>) method


Creates a rubber stamp annotation.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, System::String annotContents, System::Drawing::Color color, System::SharedPtr<System::IO::Stream> appearanceStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The number of original page where the annotation will be created. |
| annotRect | System::Drawing::Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | System::String | The contents of the annotation. |
| color | System::Drawing::Color | The colour of the annotation. |
| appearanceStream | System::SharedPtr\<System::IO::Stream\> | The stream of appearance file. |
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
      <para>The colour of the annotation.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>appearanceStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The stream of appearance file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
