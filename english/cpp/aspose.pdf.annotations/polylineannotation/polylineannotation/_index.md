---
title: Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor
linktitle: PolylineAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation constructor. Creates new Polyline annotation on the specified page in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.annotations/polylineannotation/polylineannotation/
---
## PolylineAnnotation::PolylineAnnotation constructor


Creates new Polyline annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::PolylineAnnotation::PolylineAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::ArrayPtr<System::SharedPtr<Point>> vertices)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The document's page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | System::ArrayPtr\<System::SharedPtr\<Point\>\> | An array of polygon vertices points. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document's page where annotation should be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation rectangle, defining the location of the annotation on the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>vertices</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>An array of polygon vertices points.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolylineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
