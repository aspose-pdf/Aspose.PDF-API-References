---
title: Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToPdf method
linktitle: CompareDocumentsToPdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToPdf method. Compares documents graphically. The comparison result is placed in a PDF document in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## GraphicalPdfComparer::CompareDocumentsToPdf method


Compares documents graphically. The comparison result is placed in a PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::CompareDocumentsToPdf(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::String resultPdfPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | The first document to compare. |
| document2 | System::SharedPtr\<Document\> | The second document to compare. |
| resultPdfPath | System::String | The target pdf file path. |
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
      <parametername>resultPdfPath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The target pdf file path.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the pages being compared are of different sizes. If resultPdfPath is null or empty string. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
