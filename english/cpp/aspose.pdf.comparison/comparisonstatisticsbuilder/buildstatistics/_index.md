---
title: Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics method
linktitle: BuildStatistics
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics method. Creates a statistics object for the result of comparing PDF pages or flat document comparison in which entire documents are compared in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/comparisonstatisticsbuilder/buildstatistics/
---
## ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) method


Creates a statistics object for the result of comparing PDF pages or flat document comparison in which entire documents are compared.

```cpp
static System::SharedPtr<TextItemComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\> | The list of differences. |

### ReturnValue

A statistics instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextItemComparisonStatistics](../../textitemcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) method


Creates a statistics object for the result of a page comparison of a PDF document.

```cpp
static System::SharedPtr<DocumentComparisonStatistics> Aspose::Pdf::Comparison::ComparisonStatisticsBuilder::BuildStatistics(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> diffs)
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffs | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\> | The list of differences. |

### ReturnValue

A statistics instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentComparisonStatistics](../../documentcomparisonstatistics/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [ComparisonStatisticsBuilder](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
