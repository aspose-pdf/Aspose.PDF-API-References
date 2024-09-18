---
title: Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToImage method
linktitle: ComparePagesToImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToImage method. Compares pages graphically. The comparison result is placed in a image in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer::ComparePagesToImage method


Compares pages graphically. The comparison result is placed in a image.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::ComparePagesToImage(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::String resultImagePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | The first page to compare. |
| page2 | System::SharedPtr\<Page\> | The second page to compare. |
| resultImagePath | System::String | The path to target image file. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first page to compare.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The second page to compare.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resultImagePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The path to target image file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the pages being compared are of different sizes. If resultImagePath is null or empty string. There is unknown saving image format. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
