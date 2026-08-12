---
title: "Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage метод"
linktitle: "AddEntryToTocPage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage метод. Создаёт заголовок на указанной странице оглавления (TOC) и связывает его с элементом TOCI в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.logicalstructure/headerelement/addentrytotocpage/
---
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<ListLIElement\>\&) method


Создаёт заголовок на указанной странице [Table](../../../aspose.pdf/table/) of Contents (TOC) и связывает его с элементом TOCI.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<ListLIElement> &tocEntry)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Объект [Page](../../../aspose.pdf/page/), представляющий страницу TOC, где должен быть создан заголовок. |
| tocEntry | const System::SharedPtr\<ListLIElement\>\& | Объект [ListLIElement](../../listlielement/), выступающий в роли записи TOCI для связывания с созданным заголовком на указанной странице TOC. |
## Примечания



Эта перегрузка решает сценарии, связанные с вложенными структурами [Table](../../../aspose.pdf/table/) of Contents (TOC), как указано в стандартах PDF/UA и PDF 1.7, где элемент **TOCI** не может быть дочерним для другого **TOCI**, а также где **TOC** не может быть вложен непосредственно под **TOCI**. Чтобы соответствовать этим структурным требованиям, вложенные записи TOC следует представлять с помощью элементов **List** и **[ListLIElement](../../listlielement/)**. Этот метод облегчает связывание элемента заголовка с таким [ListLIElement](../../listlielement/) на назначенной странице TOC, обеспечивая правильную логическую структуру и улучшая возможности навигации в тегированных PDF‑документах.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [ListLIElement](../../listlielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
## HeaderElement::AddEntryToTocPage(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<TOCIElement\>\&) method


Создаёт заголовок на указанной странице [Table](../../../aspose.pdf/table/) of Contents (TOC) и связывает его с элементом TOCI.

```cpp
void Aspose::Pdf::LogicalStructure::HeaderElement::AddEntryToTocPage(const System::SharedPtr<Aspose::Pdf::Page> &tocPage, const System::SharedPtr<TOCIElement> &tocEntry)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| tocPage | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Объект [Page](../../../aspose.pdf/page/), представляющий страницу TOC, где должен быть создан заголовок. |
| tocEntry | const System::SharedPtr\<TOCIElement\>\& | Элемент [TOCIElement](../../tocielement/), служащий записью TOC для связывания с создаваемым заголовком. |
## Примечания



Этот метод гарантирует корректную привязку заголовка к странице TOC и элементу TOCI, поддерживая логическую иерархию документа и обеспечивая навигацию в тегированных PDF‑структурах.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [TOCIElement](../../tocielement/)
* Class [HeaderElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
