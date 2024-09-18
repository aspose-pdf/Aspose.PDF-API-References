---
title: Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator::GenerateOutput method
linktitle: GenerateOutput
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator::GenerateOutput method. Generates the output based on the differences between texts and saves it to a file in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison.outputgenerator/ifileoutputgenerator/generateoutput/
---
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>, System::String) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual void Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Aspose::Pdf::Comparison::Diff::DiffOperation>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\> | The list of differences between texts. |
| targetFilePath | System::String | The path of the target file to save the output. |

## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../../)
* Library [Aspose.PDF for C++](../../../)
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\>, System::String) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual void Aspose::Pdf::Comparison::OutputGenerator::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Aspose::Pdf::Comparison::Diff::DiffOperation>>>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Comparison::Diff::DiffOperation\>\>\>\>\> | The list of differences between texts. |
| targetFilePath | System::String | The path of the target file to save the output. |

## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison::OutputGenerator](../../)
* Library [Aspose.PDF for C++](../../../)
