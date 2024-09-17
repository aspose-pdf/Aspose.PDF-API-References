---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations method
linktitle: ExtractAnnotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations method. Gets the list of annotations of the specified types in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, System::ArrayPtr\<System::String\>) method


Gets the list of annotations of the specified types.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Aspose::Pdf::Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, System::ArrayPtr<System::String> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int32_t | Start page from which the annotations will be selected. |
| end | int32_t | End page to which the annotations will be selected. |
| annotTypes | System::ArrayPtr\<System::String\> | The array of needed annotation types. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page from which the annotations will be selected.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page to which the annotations will be selected.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotTypes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array of needed annotation types.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\>) method


Gets the list of annotations of the specified types.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Aspose::Pdf::Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, System::ArrayPtr<Aspose::Pdf::Annotations::AnnotationType> annotTypes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int32_t | Start page from which the annotations will be selected. |
| end | int32_t | End page to which the annotations will be selected. |
| annotTypes | System::ArrayPtr\<Aspose::Pdf::Annotations::AnnotationType\> | The array of needed annotation types. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page from which the annotations will be selected.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page to which the annotations will be selected.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotTypes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array of needed annotation types.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
