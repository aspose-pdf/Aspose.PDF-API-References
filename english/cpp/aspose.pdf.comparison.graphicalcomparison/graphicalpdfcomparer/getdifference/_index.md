---
title: Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::GetDifference method
linktitle: GetDifference
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::GetDifference method. Gets differences between pages images. The result contains an image of the first page compared and an array of differences in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/getdifference/
---
## GraphicalPdfComparer::GetDifference method


Gets differences between pages images. The result contains an image of the first page compared and an array of differences.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<ImagesDifference> Aspose::Pdf::Comparison::GraphicalComparison::GraphicalPdfComparer::GetDifference(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | The first page. |
| page2 | System::SharedPtr\<Page\> | The second page. |

### ReturnValue

The [ImagesDifference](../../imagesdifference/) instance.
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

* Class [ImagesDifference](../../imagesdifference/)
* Class [Page](../../../aspose.pdf/page/)
* Class [GraphicalPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
