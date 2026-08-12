---
title: "Método Aspose::Pdf::Facades::PdfFileMend::AddImage"
linktitle: "AddImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileMend::AddImage. Añade una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.facades/pdffilemend/addimage/
---
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de imagen de entrada. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Los números de páginas que recibirán la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de imagen de entrada. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Los números de páginas que recibirán la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Los parámetros de composición gráfica para las imágenes. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) method


Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de imagen de entrada. |
| pageNum | int32_t | El número de página que recibirá la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de imagen de entrada. |
| pageNum | int32_t | El número de página que recibirá la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Los parámetros de composición gráfica para la imagen. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageName | const System::String\& | La ruta del archivo de imagen de entrada. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Los números de páginas que recibirán la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageName | const System::String\& | La ruta del archivo de imagen de entrada. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Los números de páginas que recibirán la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Los parámetros de composición gráfica para las imágenes. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float) method


Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageName | const System::String\& | La ruta del archivo de imagen de entrada. |
| pageNum | int32_t | El número de página que recibirá la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageName | const System::String\& | La ruta del archivo de imagen de entrada. |
| pageNum | int32_t | El número de página que recibirá la imagen. |
| lowerLeftX | float | La coordenada x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | float | La coordenada y inferior izquierda del rectángulo de la imagen. |
| upperRightX | float | La coordenada x superior derecha del rectángulo de la imagen. |
| upperRightY | float | La coordenada y superior derecha del rectángulo de la imagen. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Los parámetros de composición gráfica para las imágenes. |

### ReturnValue

Verdadero si tiene éxito, falso en caso contrario.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
