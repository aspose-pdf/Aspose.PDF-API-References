---
title: Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput method
linktitle: GenerateOutput
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput method. Generates the output based on the differences between texts and saves it to a file in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison/ifileoutputgenerator/generateoutput/
---
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\> | The list of differences between texts. |
| targetFilePath | System::String | The path of the target file to save the output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) method


Generates the output based on the differences between texts and saves it to a file.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| diffrences | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\> | The list of differences between texts. |
| targetFilePath | System::String | The path of the target file to save the output. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
