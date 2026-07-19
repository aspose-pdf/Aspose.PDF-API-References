---
title: "Класс Aspose::Pdf::PageCollectionExtensions"
linktitle: "PageCollectionExtensions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PageCollectionExtensions. Представляет метод‑расширение для обновления нумерации верхних и нижних колонтитулов в C++."
type: docs
weight: 13300
url: /ru/cpp/aspose.pdf/pagecollectionextensions/
---
## PageCollectionExtensions class


Представляет метод‑расширение для обновления нумерации заголовков и нижних колонтитулов.

```cpp
class PageCollectionExtensions
```

## Методы

| Метод | Описание |
| --- | --- |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) | Добавляет нумерацию Бейтса к каждой странице в заданной коллекции страниц, используя указанное действие для настройки [BatesNArtifact](../batesnartifact/). |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) | Добавляет указанный артефакт нумерации Бейтса к каждой странице в заданной коллекции страниц. |
| static [AddPagination](./addpagination/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<PaginationArtifact\>\>\>\&) | Добавляет указанные артефакты нумерации к каждой странице в заданной коллекции страниц. |
| static [DeleteBatesNumbering](./deletebatesnumbering/)(const System::SharedPtr\<PageCollection\>\&) | Удаляет все артефакты нумерации Бейтса с каждой страницы в заданной коллекции страниц. |
| [PageCollectionExtensions](./pagecollectionextensions/)() |  |
| static [UpdatePagination](./updatepagination/)(const System::SharedPtr\<PageCollection\>\&) | Обновляет номера страниц и даты в верхних и нижних колонтитулах для всех страниц. Это сработает, если документ содержит хотя бы один артефакт нумерации со специальными настройками. Все страницы в коллекции будут обновлены с использованием исходного артефакта согласно его настройкам. |
## См. также

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
