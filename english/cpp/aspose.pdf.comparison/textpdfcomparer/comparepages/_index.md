---
title: Aspose::Pdf::Comparison::TextPdfComparer::ComparePages method
linktitle: ComparePages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::ComparePages method. Compares document pages in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.comparison/textpdfcomparer/comparepages/
---
## TextPdfComparer::ComparePages method


Compares document pages.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::ComparePages(System::SharedPtr<Page> page1, System::SharedPtr<Page> page2, System::SharedPtr<ComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page1 | System::SharedPtr\<Page\> | First page. |
| page2 | System::SharedPtr\<Page\> | Second page. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |

### ReturnValue

The list of changes.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_comparison" kindref="compound">Comparison</ref> options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
