---
title: "Метод Aspose::Pdf::DocumentExtensions::SplitSharedImages"
linktitle: "SplitSharedImages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::DocumentExtensions::SplitSharedImages. Для изображений в Resources, если две страницы проверяют общие XImages и в похожих случаях разделяют их, создавая дублирующие XImages в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/documentextensions/splitsharedimages/
---
## DocumentExtensions::SplitSharedImages method


Для изображений в [Resources](../../resources/) если две страницы проверяют общие XImages и в похожих случаях разделяют их, создавая дублирующие XImages.

```cpp
static void Aspose::Pdf::DocumentExtensions::SplitSharedImages(const System::SharedPtr<Document> &doc, const System::SharedPtr<Page> &page_1, const System::SharedPtr<Page> &page_2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| док | const System::SharedPtr\<Document\>\& | Документ, содержащий обе коллекции. |
| page_1 | const System::SharedPtr\<Page\>\& | Первая страница для сравнения. |
| page_2 | const System::SharedPtr\<Page\>\& | Вторая страница для сравнения/ |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Page](../../page/)
* Class [DocumentExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
