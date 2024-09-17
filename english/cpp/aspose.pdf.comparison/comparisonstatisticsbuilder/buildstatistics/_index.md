---
title: Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics method
linktitle: BuildStatistics
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics method. Creates a statistics object for the result of comparing PDF pages or flat document comparison in which entire documents are compared in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/comparisonstatisticsbuilder/buildstatistics/
---
## ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>) method


Creates a statistics object for the result of comparing PDF pages or flat document comparison in which entire documents are compared.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\> | The list of differences. |

### ReturnValue

A statistics instance.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>diffs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The list of differences.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>\>\>) method


Creates a statistics object for the result of a page comparison of a PDF document.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Diff::DiffOperation\>\>\>\>\> | The list of differences. |

### ReturnValue

A statistics instance.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>diffs</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The list of differences.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
