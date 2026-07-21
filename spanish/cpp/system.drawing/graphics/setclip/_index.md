---
title: "Método System::Drawing::Graphics::SetClip"
linktitle: "SetClip"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Drawing::Graphics::SetClip. Establece la región de recorte de la superficie de dibujo representada por el objeto Graphics actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada por una ruta gráfica en C++."
type: docs
weight: 8600
url: /es/cpp/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada por una ruta gráfica.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | const SharedPtr\<Drawing2D::GraphicsPath\>\& | Especifica una región para combinar |
| combineMode | Drawing2D::CombineMode | Especifica la operación de combinación |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


NO IMPLEMENTADO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| región | const SharedPtr\<Region\>\& | Especifica una región para combinar |
| combineMode | Drawing2D::CombineMode | Especifica la operación de combinación |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectángulo | Especifica una región para combinar |
| combineMode | Drawing2D::CombineMode | Especifica la operación de combinación |

## Ver también

* Class [Rectangle](../../rectangle/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


Establece la región de recorte de la superficie de dibujo representada por el objeto [Graphics](../) actual al resultado de la operación especificada que combina la región de recorte actual y la región especificada.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | RectangleF | Especifica una región para combinar |
| combineMode | Drawing2D::CombineMode | Especifica la operación de combinación |

## Ver también

* Class [RectangleF](../../rectanglef/)
* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
