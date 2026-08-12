---
title: "System::Drawing::Graphics::DrawString method"
linktitle: "DrawString"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Graphics::DrawString method. Dibuja la cadena especificada en la ubicación especificada usando la fuente y el brush especificados en C++."
type: docs
weight: 2800
url: /es/cpp/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | La cadena a dibujar |
| font | const SharedPtr\<Font\>\& | Una fuente para usar |
| brush | const SharedPtr\<Brush\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| x | float | La coordenada X de la ubicación de la esquina superior izquierda de la cadena dibujada |
| y | float | La coordenada Y de la ubicación de la esquina superior izquierda de la cadena dibujada |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Especifica el formato de la cadena |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Dibuja la cadena especificada en la ubicación especificada usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | La cadena a dibujar |
| font | const SharedPtr\<Font\>\& | Una fuente para usar |
| brush | const SharedPtr\<Brush\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| topLeft | PointF | Especifica la ubicación de la esquina superior izquierda de la cadena dibujada |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Especifica el formato de la cadena |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Dibuja la cadena especificada en el rectángulo especificado usando la fuente y el pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | La cadena a dibujar |
| font | const SharedPtr\<Font\>\& | Una fuente para usar |
| brush | const SharedPtr\<Brush\>\& | Un objeto [Brush](../../brush/) para usar en el dibujo |
| layoutRectangle | RectangleF | Especifica un rectángulo en el que dibujar la cadena |
| stringFormat | const System::SharedPtr\<System::Drawing::StringFormat\>\& | Especifica el formato de la cadena |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
