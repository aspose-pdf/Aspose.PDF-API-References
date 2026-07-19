---
title: "Aspose::Pdf::Annotations::AnnotationCollection::Add method"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AnnotationCollection::Add метод. Добавляет аннотацию в коллекцию в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.annotations/annotationcollection/add/
---
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&) method


Добавляет аннотацию в коллекцию.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) который будет добавлен. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&, bool) method


Добавляет аннотацию в коллекцию. Если страница повернута, то прямоугольник аннотации будет пересчитан соответствующим образом.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation, bool considerRotation)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Annotation](../../annotation/) который будет добавлен. |
| considerRotation | bool | Если true и если страница повернута, то позиция аннотации будет пересчитана в соответствии с поворотом страницы. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
