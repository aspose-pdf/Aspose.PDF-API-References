---
title: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor"
linktitle: "LineAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation constructor. Crea una nueva anotación de línea en la página especificada en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.annotations/lineannotation/lineannotation/
---
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Crea una nueva anotación de Línea en la página especificada.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\\<Aspose::Pdf::Page\\>\\& | La página del documento donde se debe crear la anotación. |
| rect | const System::SharedPtr\<Rectangle\>\& | El rectángulo de la anotación, que define la ubicación de la anotación en la página. |
| inicio | const System::SharedPtr\<Point\>\& | Un punto, que especifica la coordenada inicial de la línea. |
| end | const System::SharedPtr\<Point\>\& | Un punto que especifica la coordenada final de la línea. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## LineAnnotation::LineAnnotation(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Point\>\&, const System::SharedPtr\<Point\>\&) constructor


Constructor para usar con Generator.

```cpp
Aspose::Pdf::Annotations::LineAnnotation::LineAnnotation(const System::SharedPtr<Document> &document, const System::SharedPtr<Point> &start, const System::SharedPtr<Point> &end)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Documento](../../../aspose.pdf/document/) donde se creará la anotación. |
| inicio | const System::SharedPtr\<Point\>\& | Punto de inicio. |
| end | const System::SharedPtr\<Point\>\& | Punto final. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Point](../../../aspose.pdf/point/)
* Class [LineAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
