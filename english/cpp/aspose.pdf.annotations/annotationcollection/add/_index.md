---
title: Aspose::Pdf::Annotations::AnnotationCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AnnotationCollection::Add method. Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.annotations/annotationcollection/add/
---
## AnnotationCollection::Add(System::SharedPtr\<Annotation\>, bool) method


Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::AnnotationCollection::Add(System::SharedPtr<Annotation> annotation, bool considerRotation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotation | System::SharedPtr\<Annotation\> | [Annotation](../../annotation/) which shall be added. |
| considerRotation | bool | If true and if page is rotated then annotation position will be recaculated accroding to page rotation. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>annotation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_annotations_1_1_annotation" kindref="compound">Annotation</ref> which shall be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>considerRotation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If true and if page is rotated then annotation position will be recaculated accroding to page rotation.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&) method


Adds annotation to the collection.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) which shall be added. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>annotation</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_annotations_1_1_annotation" kindref="compound">Annotation</ref> which shall be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
