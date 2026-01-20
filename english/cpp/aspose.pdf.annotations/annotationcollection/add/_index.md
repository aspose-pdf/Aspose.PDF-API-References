---
title: Aspose::Pdf::Annotations::AnnotationCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AnnotationCollection::Add method. Adds annotation to the collection in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.annotations/annotationcollection/add/
---
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&) method


Adds annotation to the collection.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) which shall be added. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AnnotationCollection::Add(System::SharedPtr\<Annotation\>, bool) method


Adds annotation to the collection. If page is rotated then annotation rectangle will be recalculated accordingly.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(System::SharedPtr<Annotation> annotation, bool considerRotation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| annotation | System::SharedPtr\<Annotation\> | [Annotation](../../annotation/) which shall be added. |
| considerRotation | bool | If true and if page is rotated then annotation position will be recaculated accroding to page rotation. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
