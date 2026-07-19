---
title: "Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage method"
linktitle: "CompareDocumentsPageByPage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage. Сравнивает два документа постранично в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) method


Сравнивает два документа постранично.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Первый документ.. |
| document2 | const System::SharedPtr\<Document\>\& | Второй документ. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Сравнение](../../) параметры. |

### ReturnValue

Список изменений по страницам.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) method


Сравнивает два документа постранично. Результат сохраняется в PDF‑файл.

```cpp
static System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareDocumentsPageByPage(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<ComparisonOptions> &options, const System::String &resultPdfDocumentPath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Первый документ.. |
| document2 | const System::SharedPtr\<Document\>\& | Второй документ. |
| options | const System::SharedPtr\<ComparisonOptions\>\& | [Сравнение](../../) параметры. |
| resultPdfDocumentPath | const System::String\& | Путь к PDF‑файлу для сохранения результатов сравнения. |

### ReturnValue

Список изменений по страницам.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [String](../../../system/string/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
