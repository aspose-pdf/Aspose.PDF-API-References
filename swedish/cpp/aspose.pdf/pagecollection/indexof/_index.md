---
title: "Aspose::Pdf::PageCollection::IndexOf metod"
linktitle: "IndexOf"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollection::IndexOf metod. Returnerar index för den angivna sidan i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf/pagecollection/indexof/
---
## PageCollection::IndexOf method


Returnerar index för den angivna sidan.

```cpp
int32_t Aspose::Pdf::PageCollection::IndexOf(const System::SharedPtr<Page> &entity) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entity | const System::SharedPtr\<Page\>\& | [Page](../../page/) objekt. Sidnummer börjar från 1. |

### ReturnValue

Sidans index i samlingen.
## Anmärkningar


Sidnummer börjar från 1. Returnerar 0 om samlingen inte innehåller sidan.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
