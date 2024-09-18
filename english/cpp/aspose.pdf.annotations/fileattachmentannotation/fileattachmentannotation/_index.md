---
title: Aspose::Pdf::Annotations::FileAttachmentAnnotation::FileAttachmentAnnotation constructor
linktitle: FileAttachmentAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FileAttachmentAnnotation::FileAttachmentAnnotation constructor. Creates new FileAttachment annotation on the specified page in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.annotations/fileattachmentannotation/fileattachmentannotation/
---
## FileAttachmentAnnotation::FileAttachmentAnnotation constructor


Creates new FileAttachment annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::FileAttachmentAnnotation::FileAttachmentAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::SharedPtr<FileSpecification> fileSpec)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | [Document](../../../aspose.pdf/document/)'s page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | Required rectangle that sets annotation's border. |
| fileSpec | System::SharedPtr\<FileSpecification\> | Describes the file that shoud be bound with the annotation. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref>'s page where annotation should be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Required rectangle that sets annotation's border.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fileSpec</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Describes the file that shoud be bound with the annotation.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [FileSpecification](../../../aspose.pdf/filespecification/)
* Class [FileAttachmentAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
