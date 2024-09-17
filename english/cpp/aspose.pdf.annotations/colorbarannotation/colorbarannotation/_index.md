---
title: Aspose::Pdf::Annotations::ColorBarAnnotation::ColorBarAnnotation constructor
linktitle: ColorBarAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ColorBarAnnotation::ColorBarAnnotation constructor. Creates new ColorBar annotation on the specified page in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.annotations/colorbarannotation/colorbarannotation/
---
## ColorBarAnnotation::ColorBarAnnotation constructor


Creates new ColorBar annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::ColorBarAnnotation::ColorBarAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, ColorsOfCMYK colorOfCMYK=Aspose::Pdf::Annotations::ColorsOfCMYK::Black)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | [Document](../../../aspose.pdf/document/)'s page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | Required rectangle that sets annotation's drawing area. |
| colorOfCMYK | ColorsOfCMYK | [Color](../../../aspose.pdf/color/) for which annotation drawing. |
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
      <para>Required rectangle that sets annotation's drawing area.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>colorOfCMYK</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_color" kindref="compound">Color</ref> for which annotation drawing.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Enum [ColorsOfCMYK](../../colorsofcmyk/)
* Class [ColorBarAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
