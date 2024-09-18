---
title: Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToImages method
linktitle: CompareDocumentsToImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToImages method. Compares documents graphically. The comparison result is placed in images in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer::CompareDocumentsToImages method


Compares documents graphically. The comparison result is placed in images.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToImages(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::String targetDirectory, System::String fileNamePrefix, System::SharedPtr<System::Drawing::Imaging::ImageFormat> imageFormat)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | The first document to compare. |
| document2 | System::SharedPtr\<Document\> | The second document to compare. |
| targetDirectory | System::String | The directory to save a comparison results. |
| fileNamePrefix | System::String | The images name prefix. |
| imageFormat | System::SharedPtr\<System::Drawing::Imaging::ImageFormat\> | The image format to save. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first document to compare.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>document2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The second document to compare.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>targetDirectory</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The directory to save a comparison results.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fileNamePrefix</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The images name prefix.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>imageFormat</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The image format to save.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the pages being compared are of different sizes. If targetDirectory is null or empty string. If fileNamePrefix is null or empty string. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
