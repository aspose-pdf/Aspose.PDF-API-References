---
title: Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation constructor
linktitle: PolygonAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation constructor. Constructor for using with Generator in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.annotations/polygonannotation/polygonannotation/
---
## PolygonAnnotation::PolygonAnnotation(System::SharedPtr\<Document\>, System::ArrayPtr\<System::SharedPtr\<Point\>\>) constructor


Constructor for using with Generator.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(System::SharedPtr<Document> document, System::ArrayPtr<System::SharedPtr<Point>> vertices)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Document\> | [Document](../../../aspose.pdf/document/) where annotation will be added. |
| vertices | System::ArrayPtr\<System::SharedPtr\<Point\>\> | Array of points. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> where annotation will be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>vertices</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of points.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PolygonAnnotation::PolygonAnnotation(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::ArrayPtr\<System::SharedPtr\<Point\>\>) constructor


Creates new Polygon annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::PolygonAnnotation::PolygonAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::ArrayPtr<System::SharedPtr<Point>> vertices)
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
* Class [PolygonAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
