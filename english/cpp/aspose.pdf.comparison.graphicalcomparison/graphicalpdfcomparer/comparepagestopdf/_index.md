---
title: Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToPdf method
linktitle: ComparePagesToPdf
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToPdf method. Compares pages graphically. The comparison result is placed in a PDF document in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/comparepagestopdf/
---
## GraphicalPdfComparer::ComparePagesToPdf(System::SharedPtr\<Page\>, System::SharedPtr\<Page\>, System::String) method


Compares pages graphically. The comparison result is placed in a PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToPdf(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::String resultPdfPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | The first page. |
| page2 | System::SharedPtr\<Page\> | The second page. |
| resultPdfPath | System::String | The path to target pdf file. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The second page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resultPdfPath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The path to target pdf file.</para>
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

* Class [Page](../../../aspose.pdf/page/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
## GraphicalPdfComparer::ComparePagesToPdf(System::SharedPtr\<Page\>, System::SharedPtr\<Page\>, System::SharedPtr\<Document\>) method


Compares pages graphically. The comparison result is placed in a PDF document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToPdf(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::SharedPtr<Document> pdfDocument)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | The first page. |
| page2 | System::SharedPtr\<Page\> | The second page. |
| pdfDocument | System::SharedPtr\<Document\> | The pdf document instance. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The second page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pdfDocument</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf document instance.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the pages being compared are of different sizes.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Document](../../../aspose.pdf/document/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
