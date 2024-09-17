---
title: Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics method
linktitle: CreateComparisonStatistics
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics method. Gets comparison statistics in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/
---
## TextPdfComparer::CreateComparisonStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>) method


Gets comparison statistics.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\> | The list of changes. |

### ReturnValue

The statistics.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>diffs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The list of changes.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CreateComparisonStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>\>\>) method


Gets documents comparison statistics.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::TextPdfComparer::CreateComparisonStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>\>\> | The list of changes. |

### ReturnValue

The statistics.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>diffs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The list of changes.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
