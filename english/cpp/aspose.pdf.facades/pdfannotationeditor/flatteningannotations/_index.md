---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations method
linktitle: FlatteningAnnotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations method. Flattens all annotations in the document in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## PdfAnnotationEditor::FlatteningAnnotations() method


Flattens all annotations in the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations()
```

## See Also

* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(System::SharedPtr\<Forms::Form::FlattenSettings\>) method


Flattens all annotations in the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(System::SharedPtr<Forms::Form::FlattenSettings> flattenSettings)
```


| Parameter | Type | Description |
| --- | --- | --- |
| flattenSettings | System::SharedPtr\<Forms::Form::FlattenSettings\> | Specifies modes of flattening. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>flattenSettings</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Specifies modes of flattening.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::FlatteningAnnotations(int32_t, int32_t, System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\>) method


Flattens the annotations of the specified types.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::FlatteningAnnotations(int32_t start, int32_t end, System::ArrayPtr<Aspose::Pdf::Annotations::AnnotationType> annotType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int32_t | The start page. |
| end | int32_t | Then end page. |
| annotType | System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\> | The annotation types should be flattened. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The start page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Then end page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotType</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation types should be flattened.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
