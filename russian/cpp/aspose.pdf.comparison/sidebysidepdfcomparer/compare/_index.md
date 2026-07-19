---
title: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method"
linktitle: "Compare"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare method. Сравнивает два документа. Страницы сравниваются по одной. Страницы сравниваемых документов копируются последовательно в результирующий документ. Сначала первая страница из первого документа, затем первая страница из второго документа. Затем вторая страница из первого документа и затем вторая страница из второго документа и т.д. Вы можете открыть его в Adobe Acrobat в режиме двухстраничного просмотра, чтобы увидеть изменения рядом. Удаления отмечаются на странице слева, а вставки — на странице справа в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Сравнивает два документа. Страницы сравниваются по одной. Страницы сравниваемых документов копируются последовательно в результирующий документ. Сначала первая страница из первого документа, затем первая страница из второго документа. Затем вторая страница из первого документа и вторая страница из второго документа и т.д. Вы можете открыть его в Adobe Acrobat в режиме «Двухстраничный просмотр», чтобы увидеть изменения рядом. Удаления отмечены на странице слева, вставки — на странице справа.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Первый документ для сравнения. |
| document2 | const System::SharedPtr\<Document\>\& | Второй документ для сравнения. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | Целевой поток для сохранения результата сравнения. |
| опции | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Параметры сравнения. |

### ReturnValue

Результат сравнения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Сравнивает два документа. Страницы сравниваются по одной. Страницы сравниваемых документов копируются последовательно в результирующий документ. Сначала первая страница из первого документа, затем первая страница из второго документа. Затем вторая страница из первого документа и вторая страница из второго документа и т.д. Вы можете открыть его в Adobe Acrobat в режиме «Двухстраничный просмотр», чтобы увидеть изменения рядом. Удаления отмечены на странице слева, вставки — на странице справа.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | Первый документ для сравнения. |
| document2 | const System::SharedPtr\<Document\>\& | Второй документ для сравнения. |
| targetPdfPath | const System::String\& | Путь к PDF-файлу для сохранения результата сравнения. |
| опции | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Параметры сравнения. |

### ReturnValue

Результат сравнения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Сравнивает две страницы. Результат сохраняется в PDF‑документе, в котором первая страница записывается первой, затем вторая. Вы можете открыть его в Adobe Acrobat в режиме «Двухстраничный просмотр», чтобы увидеть изменения рядом. Удаления отмечены на странице слева, вставки — на странице справа.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Первая страница для сравнения. |
| page2 | const System::SharedPtr\<Page\>\& | Первая страница для сравнения. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | Целевой поток для сохранения результата сравнения. |
| опции | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Параметры сравнения. |

### ReturnValue

Результат сравнения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Сравнивает две страницы. Результат сохраняется в PDF‑документе, в котором первая страница записывается первой, затем вторая. Вы можете открыть его в Adobe Acrobat в режиме «Двухстраничный просмотр», чтобы увидеть изменения рядом. Удаления отмечены на странице слева, вставки — на странице справа.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | Первая страница для сравнения. |
| page2 | const System::SharedPtr\<Page\>\& | Первая страница для сравнения. |
| targetPdfPath | const System::String\& | Путь к PDF-файлу для сохранения результата сравнения. |
| опции | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Параметры сравнения. |

### ReturnValue

Результат сравнения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
