---
title: "Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation constructor"
linktitle: "InkAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation constructor. Crea una nueva anotación de tinta en la página especificada en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.annotations/inkannotation/inkannotation/
---
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Crea una nueva anotación de tinta en la página especificada.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\\<Aspose::Pdf::Page\\>\\& | La página del documento donde se debe crear la anotación. |
| rect | const System::SharedPtr\<Rectangle\>\& | El rectángulo de la anotación, que define la ubicación de la anotación en la página. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | Una matriz de matrices [Point](../../../aspose.pdf/point/)[], cada una representando una ruta trazada. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## InkAnnotation::InkAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) constructor


Constructor para la anotación de tinta para Generator.

```cpp
Aspose::Pdf::Annotations::InkAnnotation::InkAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<System::Collections::Generic::IList<System::ArrayPtr<System::SharedPtr<Point>>>> &inkList)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) donde se creará la anotación de tinta. |
| inkList | const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\& | Una matriz de matrices [Point](../../../aspose.pdf/point/)[], cada una representando una ruta trazada. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [IList](../../../system.collections.generic/ilist/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../../aspose.pdf/point/)
* Class [InkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
