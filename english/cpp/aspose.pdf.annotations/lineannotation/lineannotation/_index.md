---
title: Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor
linktitle: LineAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor. Constructor for using with Generator in C++.'
type: docs
weight: 2900
url: /cpp/aspose.pdf.annotations/lineannotation/lineannotation/
---
## LineAnnotation::LineAnnotation(System::SharedPtr\<Document\>, System::SharedPtr\<Point\>, System::SharedPtr\<Point\>) constructor


Constructor for using with Generator.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(System::SharedPtr<Document> document, System::SharedPtr<Point> start, System::SharedPtr<Point> end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Document\> | [Document](../../../aspose.pdf/document/) where annotation will be created. |
| start | System::SharedPtr\<Point\> | Starting point. |
| end | System::SharedPtr\<Point\> | Ending point. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> where annotation will be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Starting point. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Ending point. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## LineAnnotation::LineAnnotation(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::SharedPtr\<Point\>, System::SharedPtr\<Point\>) constructor


Creates new Line annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::SharedPtr<Point> start, System::SharedPtr<Point> end)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The document's page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | The annotation rectangle, defining the location of the annotation on the page. |
| start | System::SharedPtr\<Point\> | A point, specifying the starting coordinate of the line. |
| end | System::SharedPtr\<Point\> | A point, specifying the ending coordinate of the line. |
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
      <parametername>start</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A point, specifying the starting coordinate of the line.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>end</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A point, specifying the ending coordinate of the line.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
