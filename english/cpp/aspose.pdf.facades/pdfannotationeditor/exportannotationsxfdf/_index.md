---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method
linktitle: ExportAnnotationsXfdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method. Exports the content of the specified annotation types into XFDF in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<System::String\>) method


Exports the content of the specified annotation types into XFDF.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr<System::IO::Stream> xmlOutputStream, int32_t start, int32_t end, System::ArrayPtr<System::String> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | System::SharedPtr\<System::IO::Stream\> | The output XFDF stream. |
| start | int32_t | Start page from which the annotations of the document will be exported. |
| end | int32_t | End page to which the annotations of the document will be exported. |
| annotTypes | System::ArrayPtr\<System::String\> | The array of annotation types need be exported. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>xmlOutputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The output XFDF stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page from which the annotations of the document will be exported.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page to which the annotations of the document will be exported.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotTypes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array of annotation types need be exported.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\>) method


Exports the content of the specified annotations types into XFDF.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(System::SharedPtr<System::IO::Stream> xmlOutputStream, int32_t start, int32_t end, System::ArrayPtr<Aspose::Pdf::Annotations::AnnotationType> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xmlOutputStream | System::SharedPtr\<System::IO::Stream\> | The output XFDF stream. |
| start | int32_t | Start page from which the annotations of the document will be exported. |
| end | int32_t | End page to which the annotations of the document will be exported. |
| annotTypes | System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\> | The array of annotation types need be exported. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>xmlOutputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The output XFDF stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page from which the annotations of the document will be exported.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page to which the annotations of the document will be exported.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotTypes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array of annotation types need be exported.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
