---
title: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering‑metod"
linktitle: "AddBatesNumbering"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering‑metod. Lägger till det angivna Bates‑numreringsartefaktet på varje sida i den angivna sidkollektionen i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) method


Lägger till det angivna Bates-numreringsartefaktet till varje sida i den givna sidkollektionen.

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, const System::SharedPtr<BatesNArtifact> &artifact)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | Samlingsobjektet av sidor som Bates‑numreringsartefaktet ska läggas till. |
| artifact | const System::SharedPtr\<BatesNArtifact\>\& | Den [BatesNArtifact](../../batesnartifact/)‑instansen som ska läggas till på varje sida. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) method


Lägger till Bates‑numrering på varje sida i den angivna sidkollektionen med den angivna åtgärden för att konfigurera [BatesNArtifact](../../batesnartifact/).

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(const System::SharedPtr<PageCollection> &pageCollection, System::Action<System::SharedPtr<BatesNArtifact>> action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageCollection | const System::SharedPtr\<PageCollection\>\& | Samlingsobjektet av sidor som Bates‑numreringen ska läggas till. |
| action | System::Action\<System::SharedPtr\<BatesNArtifact\>\> | En åtgärd för att konfigurera [BatesNArtifact](../../batesnartifact/) innan den läggs till på varje sida. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Typedef [Action](../../../system/action/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
