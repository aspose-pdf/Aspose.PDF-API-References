---
title: "Aspose::Pdf::Annotations::AnnotationCollection::Add método"
linktitle: "Add"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AnnotationCollection::Add método. Añade la anotación a la colección en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.annotations/annotationcollection/add/
---
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&) method


Añade la anotación a la colección.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Anotación](../../annotation/) que se añadirá. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AnnotationCollection::Add(const System::SharedPtr\<Annotation\>\&, bool) method


Añade la anotación a la colección. Si la página está rotada, el rectángulo de la anotación se recalculará en consecuencia.

```cpp
void Aspose::Pdf::Annotations::AnnotationCollection::Add(const System::SharedPtr<Annotation> &annotation, bool considerRotation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotation | const System::SharedPtr\<Annotation\>\& | [Anotación](../../annotation/) que se añadirá. |
| considerRotation | bool | Si es verdadero y la página está rotada, la posición de la anotación se recalculará de acuerdo con la rotación de la página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Annotation](../../annotation/)
* Class [AnnotationCollection](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
