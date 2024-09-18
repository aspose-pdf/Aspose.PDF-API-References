---
title: Aspose::Pdf::Facades::PdfAnnotationEditor::ModifyAnnotations method
linktitle: ModifyAnnotations
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfAnnotationEditor::ModifyAnnotations method. Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, Color, Subject and Open in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor::ModifyAnnotations method


Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties: Modified, Title, Contents, [Color](../../../aspose.pdf/color/), Subject and Open.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfAnnotationEditor::ModifyAnnotations(int32_t start, int32_t end, System::SharedPtr<Aspose::Pdf::Annotations::Annotation> annotation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| start | int32_t | The start page number. |
| end | int32_t | The end page number. |
| annotation | System::SharedPtr\<Aspose::Pdf::Annotations::Annotation\> | The annotation object contains new properties. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The start page number.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The end page number.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>annotation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation object contains new properties.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
