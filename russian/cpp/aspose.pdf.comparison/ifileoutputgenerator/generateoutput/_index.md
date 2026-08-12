---
title: "Метод Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput"
linktitle: "GenerateOutput"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput. Генерирует вывод на основе различий между текстами и сохраняет его в файл в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/ifileoutputgenerator/generateoutput/
---
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) method


Генерирует вывод на основе различий между текстами и сохраняет его в файл.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>> diffrences, System::String targetFilePath)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\> | Список различий между текстами. |
| targetFilePath | System::String | Путь к целевому файлу для сохранения вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## IFileOutputGenerator::GenerateOutput(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) method


Генерирует вывод на основе различий между текстами и сохраняет его в файл.

```cpp
virtual void Aspose::Pdf::Comparison::IFileOutputGenerator::GenerateOutput(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> diffrences, System::String targetFilePath)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| различия | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\> | Список различий между текстами. |
| targetFilePath | System::String | Путь к целевому файлу для сохранения вывода. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [String](../../../system/string/)
* Class [IFileOutputGenerator](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
