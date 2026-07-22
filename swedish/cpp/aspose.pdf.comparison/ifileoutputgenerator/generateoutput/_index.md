---
title: "Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput metod"
linktitle: "GenerateOutput"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput-metod. Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.comparison/ifileoutputgenerator/generateoutput/
---
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) method


Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skillnader | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\> | Listan över skillnader mellan texter. |
| targetFilePath | System::String | Sökvägen till målfilen för att spara outputen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) method


Genererar utdata baserat på skillnaderna mellan texter och sparar den till en fil.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> diffrences, System::String targetFilePath)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skillnader | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\> | Listan över skillnader mellan texter. |
| targetFilePath | System::String | Sökvägen till målfilen för att spara outputen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
