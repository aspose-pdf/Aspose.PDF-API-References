---
title: Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator::GenerateOutput method
linktitle: GenerateOutput
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator::GenerateOutput method. Generates the output based on the differences between texts and saves it to a file in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison.outputgenerator/istringoutputgenerator/generateoutput/
---
## IStringOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual System::String Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Aspose::Pdf::Comparison::Diff::DiffOperation>>> diffrences)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\> | The list of differences between texts. |

### ReturnValue

[Text](../../../aspose.pdf.text/) representation of output.

## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [IStringOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../../)
* Library [Aspose.PDF for C++](../../../)
## IStringOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual System::String Aspose::Pdf::Comparison::OutputGenerator::IStringOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Aspose::Pdf::Comparison::Diff::DiffOperation>>>>> diffrences)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\> | The list of differences between texts. |

### ReturnValue

[Text](../../../aspose.pdf.text/) representation of output.

## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [IStringOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../../)
* Library [Aspose.PDF for C++](../../../)
