---
title: "Aspose::Pdf::Annotations::AnnotationCollection::Add-metoden"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AnnotationCollection::Add-metoden. Lägger till annotation i samlingen i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.annotations/annotationcollection/add/
---
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&) method


Lägger till annotation i samlingen.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) som ska läggas till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&, bool) method


Lägger till annotation i samlingen. Om sidan är roterad kommer annoteringsrektangeln att omräknas därefter.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation, bool considerRotation)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) som ska läggas till. |
| considerRotation | bool | Om true och om sidan är roterad kommer annotationens position att beräknas om enligt sidrotationen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
