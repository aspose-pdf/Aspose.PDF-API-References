---
title: Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering method
linktitle: AddBatesNumbering
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering method. Adds Bates numbering to each page in the given page collection using the specified action to configure the BatesNArtifact in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## PageCollectionExtensions::AddBatesNumbering(System::SharedPtr\<PageCollection\>, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) method


Adds Bates numbering to each page in the given page collection using the specified action to configure the [BatesNArtifact](../../batesnartifact/).

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(System::SharedPtr<PageCollection> pageCollection, System::Action<System::SharedPtr<BatesNArtifact>> action)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageCollection | System::SharedPtr\<PageCollection\> | The collection of pages to which the Bates numbering will be added. |
| action | System::Action\<System::SharedPtr\<BatesNArtifact\>\> | An action to configure the [BatesNArtifact](../../batesnartifact/) before adding it to each page. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Typedef [Action](../../../system/action/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollectionExtensions::AddBatesNumbering(System::SharedPtr\<PageCollection\>, System::SharedPtr\<BatesNArtifact\>) method


Adds the specified Bates numbering artifact to each page in the given page collection.

```cpp
static void Aspose::Pdf::PageCollectionExtensions::AddBatesNumbering(System::SharedPtr<PageCollection> pageCollection, System::SharedPtr<BatesNArtifact> artifact)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageCollection | System::SharedPtr\<PageCollection\> | The collection of pages to which the Bates numbering artifact will be added. |
| artifact | System::SharedPtr\<BatesNArtifact\> | The [BatesNArtifact](../../batesnartifact/) instance to be added to each page. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageCollection](../../pagecollection/)
* Class [BatesNArtifact](../../batesnartifact/)
* Class [PageCollectionExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
