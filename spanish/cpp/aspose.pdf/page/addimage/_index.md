---
title: "Aspose::Pdf::Page::AddImage método"
linktitle: "AddImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Page::AddImage método. Añade una imagen a la página y la ubica en el centro del rectángulo especificado, conservando la proporción de la imagen en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/page/addimage/
---
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) method


Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr, bool autoAdjustRectangle=true)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de la imagen. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | La posición de la imagen. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbox de la imagen. |
| autoAdjustRectangle | bool | Ajustar la imagen al centro del rectángulo de entrada. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Agrega una imagen a la página y la coloca según la posición del rectángulo de la imagen.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, System::SharedPtr<Aspose::Pdf::Rectangle> imageRect, int32_t imageWidth, int32_t imageHeight, bool saveImageProportions, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de la imagen. |
| imageRect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | La posición predeterminada de la imagen en la página. |
| imageWidth | int32_t | El ancho de la imagen. |
| imageHeight | int32_t | La altura de la imagen. |
| saveImageProportions | bool | Si la bandera se establece en true, la imagen se coloca en la posición del rectángulo; de lo contrario, el tamaño del rectángulo se vuelve igual al tamaño de la imagen. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | El bbox de la imagen. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Agrega una imagen buscable a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &hocr, const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hocr | const System::String\& | El hocr de la imagen. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de la imagen. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | La posición de la imagen. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | El bbox de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Agrega una imagen a la página y la coloca en el centro del rectángulo especificado conservando la proporción de la imagen.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &imagePath, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagePath | const System::String\& | La ruta a la imagen. |
| rectangle | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | La posición de la imagen. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
