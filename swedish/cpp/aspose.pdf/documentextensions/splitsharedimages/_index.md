---
title: "Aspose::Pdf::DocumentExtensions::SplitSharedImages metod"
linktitle: "SplitSharedImages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::DocumentExtensions::SplitSharedImages metod. För bilder i Resources kontrolleras två sidor för gemensamma XImages och i liknande fall delas de genom att skapa duplicerade XImages i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/documentextensions/splitsharedimages/
---
## DocumentExtensions::SplitSharedImages method


För bilder i [Resources](../../resources/) om två sidor kontrollerar gemensamma XImages och i liknande fall delar dem genom att skapa duplicerade XImages.

```cpp
static void Aspose::Pdf::DocumentExtensions::SplitSharedImages(const System::SharedPtr<Document> &doc, const System::SharedPtr<Page> &page_1, const System::SharedPtr<Page> &page_2)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| doc | const System::SharedPtr\<Document\>\& | Dokumentet som innehåller båda samlingarna. |
| page_1 | const System::SharedPtr\<Page\>\& | Första sidan för jämförelse. |
| page_2 | const System::SharedPtr\<Page\>\& | Andra sidan för jämförelse/ |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Page](../../page/)
* Class [DocumentExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
