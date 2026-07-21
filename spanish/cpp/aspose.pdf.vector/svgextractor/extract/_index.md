---
title: "Método Aspose::Pdf::Vector::SvgExtractor::Extract"
linktitle: "Extract"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Vector::SvgExtractor::Extract. Extrae la imagen SVG a una cadena a partir de los elementos gráficos representados por el absorber con un filtro de predicado en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.vector/svgextractor/extract/
---
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) method


Extrae la imagen SVG a una cadena desde elementos gráficos representados por [absorber](../) con un filtro de predicado.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | El objeto [GraphicsAbsorber](../../graphicsabsorber/) que contiene los elementos gráficos. |
| filtro | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | Una función de predicado utilizada para filtrar los elementos gráficos. |
| página | const System::SharedPtr\<Page\>\& | La página donde el absorber obtiene los elementos gráficos. |

### ReturnValue

La cadena con contenido SVG.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) method


Extrae una imagen svg a un archivo a partir de elementos gráficos representados por [absorber](../) con un filtro de predicado.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | El objeto [GraphicsAbsorber](../../graphicsabsorber/) que contiene los elementos gráficos. |
| filtro | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | Una función de predicado utilizada para filtrar los elementos gráficos. |
| página | const System::SharedPtr\<Page\>\& | La página donde el absorber obtiene los elementos gráficos. |
| svgFilePath | const System::String\& | La ruta del archivo SVG de destino. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&) method


Extrae imágenes Svg de una página a cadenas.

```cpp
System::SharedPtr<System::Collections::Generic::List<System::String>> Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\<Page\>\& | La página a extraer. |

### ReturnValue

La lista de cadenas de contenido SVG.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&, const System::String\&) method


Extrae imágenes Svg de una página a archivos.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page, const System::String &directory)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\<Page\>\& | La página a extraer. |
| directorio | const System::String\& | El directorio de destino donde colocar las imágenes SVG. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) method


Extrae elementos gráficos a una cadena SVG. Opciones ignoradas: agrupación, extracción desde rectángulo.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementos | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | Los elementos gráficos a convertir. |
| página | const System::SharedPtr\<Page\>\& | La página donde el absorber obtiene los elementos gráficos. |

### ReturnValue

La cadena con contenido SVG.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) method


Extrae elementos gráficos a un único archivo SVG. Opciones ignoradas: agrupación, extracción desde rectángulo.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementos | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | Los elementos gráficos a convertir. |
| página | const System::SharedPtr\<Page\>\& | La página donde el absorber obtiene los elementos gráficos. |
| svgFilePath | const System::String\& | La ruta del archivo SVG de destino. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
