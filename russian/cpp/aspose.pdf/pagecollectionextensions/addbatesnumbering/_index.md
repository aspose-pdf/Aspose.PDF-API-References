---
title: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering метод"
linktitle: "AddBatesNumbering"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering метод. Добавляет указанный артефакт нумерации Bates к каждой странице в заданной коллекции страниц в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) method


Добавляет указанный артефакт нумерации Бейтса к каждой странице в заданной коллекции страниц.

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, const System::SharedPtr<BatesNArtifact> &artifact)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | Коллекция страниц, к которой будет добавлен артефакт нумерации Bates. |
| artifact | const System::SharedPtr\<BatesNArtifact\>\& | Экземпляр [BatesNArtifact](../../batesnartifact/) для добавления к каждой странице. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) method


Добавляет нумерацию Bates к каждой странице в заданной коллекции страниц, используя указанное действие для настройки [BatesNArtifact](../../batesnartifact/).

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, System::Action<System::SharedPtr<BatesNArtifact>> action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | Коллекция страниц, к которым будет добавлена нумерация Бейтса. |
| action | System::Action\<System::SharedPtr\<BatesNArtifact\>\> | Действие по настройке [BatesNArtifact](../../batesnartifact/) перед добавлением его на каждую страницу. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Typedef [Action](../../../system/action/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
